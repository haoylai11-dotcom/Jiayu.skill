# Jiayu.skill 💎

Growth Marketing Skill distilled from Jiayu Xie's workflow at [Kuse Inc.](https://kuse.ai) (2026 Q1-Q2).

An AI-readable skill package that captures growth marketing expertise — designed to be loaded by AI agents (OpenClaw, Hermes, etc.) so they can execute KOL research, SEO campaigns, and ambassador programs autonomously.

## What's Inside

### 🎯 KOL/KOC Research & Evaluation
- **Sourcing pipeline**: In-house (Apify + competitor scraping + regional keyword search) and external agency workflows
- **Analysis framework**: 9-dimension evaluation (product fit, region, subscribers, upload frequency, median likes, avg views, content type, sponsorship ratio)
- **播粉比 benchmarks**: Calibrated from 35+ real channel analyses across JP/KR/US/PL markets
- **ICP matching**: Dual-product logic (Kuse AI for individuals vs Junior for enterprises)
- **Data collection**: Apify scrapers, curl/HTML fallbacks, oEmbed tricks for non-English markets

### 🤝 Ambassador Program
- Three-tier system (Partner → Ambassador → Pioneer)
- Complete playbook: pitch templates, briefing flow, contract terms, onboarding steps
- Japan market-specific notes and templates

### 🔗 SEO & Backlink
- **Backlink Comment Tool** (Chrome extension): Ahrefs-powered competitive backlink commenting
- **Backlink Pilot** (CLI): Bulk directory submission to 259+ sites
- Keyword research 6-step playbook
- DR improvement strategy

### 📺 YouTube Campaign Management
- KOL tier pricing reference (Micro/Mid/Large)
- Budget allocation frameworks
- Market priority rankings with rationale

### 📋 Also Includes
- X/Twitter outreach classification and hygiene rules
- Landing page design workflow
- Agency collaboration tips (Deeplink, 正和增长, Aha)
- Decision quick-reference table
- All relevant Lark doc links and archive references

## Structure

```
├── SKILL.md                        # Main skill file (~11.5KB)
├── references/
│   ├── analyzed-channels.md        # 35+ channels analyzed (top picks by market)
│   └── apify-workarounds.md        # Apify quirks & fallback solutions
└── README.md
```

## Usage

This skill is designed to be loaded by AI agents. Point your agent's skill directory to this repo:

```
# OpenClaw / Hermes — add to workspace skills
git clone https://github.com/haoylai11-dotcom/Jiayu.skill.git skills/jiayu-growth-marketing
```

Then ask your agent things like:
- "帮我分析这批 YouTube 频道 list"
- "找做过 Manus 视频的日本 KOL"
- "用 Backlink Pilot 提交我们的网站"
- "帮我写一个 KOL campaign brief"

## Author

**Jiayu Xie (谢佳雨)** — Head of Growth @ Kuse Inc.

Built with the help of [Rin](https://github.com/kuse-ai) 💎
