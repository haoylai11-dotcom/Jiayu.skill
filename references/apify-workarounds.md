# Apify Workarounds (Field-Tested)

## Known Issues

### 1. `streamers~youtube-channel-scraper` — Korean/Japanese handles fail
- **Symptom:** Returns 0 results for non-ASCII handles (e.g. `@알린`)
- **Fix:** Use `startUrls` format with full URL, or fall back to curl HTML scraping
- Channel IDs can be extracted via: `grep -oP '"externalId":"[^"]*"'`

### 2. YouTube search actors — non-English queries return 0
- **Symptom:** `bernardo~youtube-scraper` with Japanese/Korean keywords → empty
- **Fix:** Use `apify~google-search-scraper` with `site:youtube.com` + target language keywords
- Then extract channel info via oEmbed API

### 3. Subscriber counts not in initial HTML
- **Symptom:** Featured page doesn't show subscriber count in scraped HTML
- **Fix:** Use `/about` page + grep for accessibility label:
  ```
  grep -oP 'チャンネル登録者数 [^"]*'
  ```
- Or use the full accessibility data pattern:
  ```
  grep -oP '"subscriberCountText".*?"label":"[^"]*"'
  ```

### 4. Rate limiting
- Apify free tier: limited compute units
- YouTube HTML scraping: add `sleep 0.3-0.5` between requests
- Google search scraper: max 3 pages per query to avoid blocks

## Working Actor IDs
| Actor | ID | Works for |
|-------|-----|-----------|
| YouTube Channel Scraper | `streamers~youtube-channel-scraper` | ASCII handles only |
| Google Search Scraper | `apify~google-search-scraper` | Finding channels in any language |

## oEmbed Trick
Map video URL → channel:
```
GET https://www.youtube.com/oembed?url=https://www.youtube.com/watch?v={VIDEO_ID}&format=json
```
Returns: `author_name`, `author_url` (channel URL)
