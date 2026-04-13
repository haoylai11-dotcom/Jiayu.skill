---
name: jiayu-growth-marketing
description: "Growth marketing: KOL/KOC research & analysis, Ambassador program, SEO/backlink building, YouTube campaign management, and outreach. Use when asked to: find/evaluate YouTube KOLs, analyze channel stats, build KOL lists by market, run backlink campaigns, manage ambassador relationships, or plan GTM campaigns. Distilled from Jiayu Xie's workflow at Kuse (2026 Q1-Q2)."
---

# Growth Marketing Skill

> Distilled from Jiayu Xie (谢佳雨), Head of Growth @ Kuse Inc.
> Covers: KOL sourcing & evaluation, Ambassador Program, SEO/Backlink, YouTube Campaign, Outreach, Landing Page, Ad accounts

---

## 1. KOL/KOC Sourcing & Evaluation

### 1.1 Sourcing Channels

#### A. In-House (via Rin + Apify)

**方式一：竞品 KOL 反查**
Prompt: `帮我找做过 [竞品名 如 Manus/Genspark] 视频的 YouTube 频道，按 [地区] 市场筛选，输出推荐名单`

**方式二：地区定向搜索**
按目标市场语言搜索 AI 工具关键词：

| 市场 | 关键词 |
|------|--------|
| 🇺🇸 英语 | "AI tools review", "AI productivity", "best AI tools 2026" |
| 🇯🇵 日本 | "AIツール レビュー", "AI 仕事効率化", "AI 業務自動化" |
| 🇰🇷 韩国 | "AI 도구 리뷰", "AI 업무 효율화", "AI 자동화" |
| 🇧🇷 巴西 | "ferramentas de IA", "automatização IA negócios" |
| 🇵🇱 波兰 | "narzędzia AI produktywność", "automatyzacja AI biznes" |

#### B. External Agency

**流程:**
1. 我方提供 brief（产品信息、目标市场、预算、内容类型偏好）
   - Junior Brief: Lark `QTEsdcDN4oIxAkxDBgDl9YTBgGb`
   - Kuse Brief: Lark `VLRfdkrcvoc1cKxIQdql1zRegOg`
2. Agency 返回报价 + KOL 名单
3. 将名单 URL 发给 Rin 做独立评估（不依赖 agency 数据）

**Agency 合作 Tips:**
- 一开始画大饼：预算先不限制，地区要多样，让 agency 觉得是大客户才会积极提报
- 定期 tracking，卡点难解决时直接打电话（比文字高效很多）
- 到手名单一定让 Rin 独立验证数据

**现有 Agency:**
| Agency | 优势 | 注意 |
|--------|------|------|
| Deeplink | 日韩达人多，提报带报价，能直接推进 | 需要时不时催，他们内部会评估优先级 |
| 正和增长 | X 达人多，泛英语质量高 | YouTube 需新建联，效率慢，要催报价 |
| Aha (brand.ahacreator.com) | 详细匹配产品需求，可看达人后台画像，Ins/TT 发达国家多 | AI 建联回复率低，需要筛选 |

### 1.2 Data Collection

对每个频道采集以下维度：

Prompt: `帮我分析这批 list，从推荐合作产品（kuse/junior）+地区+link+粉丝量+发布频率+赞中位数+均播+类型+商单占比来分析：`

| 维度 | 说明 |
|------|------|
| 推荐合作产品 | Kuse AI / Junior / 都适合 |
| 地区 | JP / KR / US / EU / BR / etc. |
| 频道链接 | youtube.com/@handle |
| 粉丝量 | 订阅数 |
| 发布频率 | 日更/周更/月更/已停更 |
| 赞中位数 | 近 8 条视频点赞中位 |
| 均播 | 近 8 条视频播放量中位数 |
| 类型 | 见 §1.4 分类体系 |
| 商单占比 | 低(<10%) / 中(10-30%) / 高(>30%) |

### 1.3 Evaluation Criteria

#### 播粉比基准线（均播 / 粉丝数）

| 范围 | 判断 |
|------|------|
| >30% | 🔥 爆款/增长期，内容远超粉丝基数，高性价比 |
| 10-30% | ✅ 优秀，粉丝活跃度高 |
| 3-10% | ✅ 正常健康，行业平均水准 |
| 1-3% | ✅ 正常，大号可接受，小号需谨慎 |
| <1% | ❌ 有问题：虚粉/过气/Shorts 冲量 |

**重要：** 小频道（<10K）播粉比天然更高，大频道（>100K）维持 5% 就算强。需分段看，不能一刀切。

**均播绝对值 > 粉丝量：** 真实触达比订阅数重要。241 粉但均播 4 万的频道 > 20 万粉但均播 2 千的频道。

**CPM（报价/均播×1000）** 是核心性价比指标：<$100 = 优秀，>$300 = 偏贵

**其他维度:**
- 📅 发布频率：高频 = 活跃，低频 = 可能已放弃
- 💬 评论区质量：真实讨论 vs bot/spam，真实讨论 = 高转化
- 🤝 互动质量：创作者是否回复粉丝，高互动 = 强社区
- 🎯 产品匹配度：竞品冲突 + 受众地理要匹配目标市场

#### 优先联系信号
- ✅ 已有 OpenClaw / Kuse / Junior 相关内容 → 自发推广，合作意愿高
- ✅ 做过 2+ 条竞品视频 → 证明赛道兴趣和接单意愿
- ✅ 频道正在增长期（播粉比 >30%）→ 性价比最高
- ✅ 描述里有商务合作邮箱 → 接单体系成熟
- ✅ 有企业培训/咨询背景 → 触达有付费能力的 B 端受众

#### 排除信号
- ❌ 粉丝量大但均播极低（播粉比 <1%）→ Shorts 冲粉/买粉/过气
- ❌ 近期播放断崖下跌 → 频道衰退
- ❌ 内容太杂（AI + 手机刷机 + PPT + 无关话题）→ 受众不精准
- ❌ 地区不匹配目标市场
- ❌ 长视频只有几条，全靠 Shorts → 长视频触达接近零

### 1.4 Content Type Classification

| 类型 | 定义 | 合作适配度 |
|------|------|-----------|
| AI 工具 Review | 测评各类 AI 工具，有商单体系 | ⭐⭐⭐⭐⭐ 最适合 |
| AI 教程/Tutorial | 教用户怎么用 AI 工具 | ⭐⭐⭐⭐⭐ 最适合 |
| AI+商业/组织效率 | 教用户如何用 AI 辅助公司效率 | ⭐⭐⭐⭐ Junior 适合 |
| AI+创业/副业 | 用 AI 赚钱/做副业 | ⭐⭐⭐⭐ Kuse AI 适合 |
| AI+自动化/编程 | n8n, Claude Code 等技术向 | ⭐⭐⭐⭐ Kuse AI 适合 |
| 科技综合 | AI 只是一部分，还覆盖其他科技 | ⭐⭐⭐ 看具体内容占比 |
| 设计/创意工具 | Photoshop, 视频生成为主 | ⭐⭐ 除非有 AI workspace 角度 |
| 非 AI 垂类 | 语言学习/房产/健康等 | ⭐ 通常不推荐 |

### 1.5 Product Matching

**Kuse AI（$39.9-$199.9/月，个人 AI workspace）：**
- 目标受众：个人用户、freelancer、独立开发者、白领
- 适合频道画像：AI 工具用户、独立创业者/一人公司、内容创作者、AI 副业方向

**Junior（$2,000/月，组织级 AI 员工）：**
- 目标受众：中小企业主、团队管理者
- 适合频道画像：企业管理者/CEO/创始人、有团队协作需求、B2B SaaS 决策者、有企业培训/咨询背景的 KOL 受众

**Both**: 频道主有企业咨询背景 + 个人向内容

---

## 2. Ambassador Program

### 2.1 Three-Tier System

| Tier | 要求 | 福利 |
|------|------|------|
| 🥉 Partner | 1篇原创内容 + tag @hirejuniorso | $200 credits + badge |
| 🥈 Ambassador | 每月2篇 + 1篇高互动 + 产品反馈 | 免费 Junior + 早期 feature access + 季度1v1 |
| 🥇 Pioneer | 持续高质量 + 直接带客 | Revenue share 15% + 产品共创权 + 区域负责人优先 |

### 2.2 Full Process: Pitch → List → Brief → Contract → Onboarding

**一、Pitch 文案**

*A. 已经发过 Junior/Kuse 内容的 KOL:*

> 你好！我是 Kuse 团队的 [名字]。
> 首先非常感谢你之前发布的关于 Junior 的内容！你的介绍写得非常准确，帮助了很多日本用户了解 AI 员工这个新概念。
> 也跟你同步一下进展：launch video 拿到了 180 万+曝光，launch 3 天内 close 了 2 家日本企业 deal，waitlist 上还有超过 50 家日本企业在排队。
> 我们非常重视日本市场，希望和真正理解这个产品的创作者建立长期关系：
> • 4 月将参加 Sushi Tech Tokyo
> • 正在建立日本区 Ambassador Program
> • 未来有设立日本办事处的计划
> 想跟你聊一下后续的长期合作可能性。形式完全开放，你可以直接提方案。Ambassador Program 会优先考虑像你这样早期就关注到 Junior 的创作者。
> 感兴趣的话可以直接邮件联系我们：[email]

**二、确定 List**

**三、讲解计划**
- 发 JP 资料给 KOL，讲解 Junior 是 toB 产品，社媒持续推广有难度
- 所以 ambassador 结合 Kuse 和 Junior，给更大的内容创作空间
- Lark 资料: `L5R9wwKsOivCYek1F6alqvIBgfh` (EN) / `HgNewLssdixHObkcimVlsCoVg4d` (JP)
- 补充（私下说）：三条内容中可有一条 quote，另两条需原创（鼓励原创，也比较好投流）
- 隐藏福利：推荐其他大使加入，稳定运营 3 个月可获 $100
- 第一次线上约会主要讲背景和计划详情，看对方是否接受
- 讲稿参考: Lark `Z9AGwkWrniOwPmkjyAileA8BgPb`
- PPT: Figma `c2vLpDbyN5T0PizEzV4ZrU/Kuse-for-Japan-KOLs`

**四、确定合作 + 签订合同**
1. 发合同给对方看（highlight 需填部分）: Lark `M3Ykwkpnmia5MqkecRUlPE1egOt`
2. 对方确认后收集信息（全英文）：
   - Ambassador 名称、Name、Email
   - W8 报税表（个人）或 W8-E（企业）+ Invoice
   - 付款信息：受取人名、银行名、账号(USD/IBAN)、SWIFT Code、银行地址、住所(含邮编)
3. 信息收齐后发给 Yulia，Yulia 通过 WeSign 发正式合同

**五、Onboarding**
- 产品讲解由 Xiaoning + Austin 负责
- **Kuse:** 在 Slack 群内申请 15K credits
- **Junior:** 让 Sibo 为每人建专属 Slack Channel，拉 Rin 进去
- Xiaoning 也进群，用 case 带他们上手，活跃气氛
- 每月会议同步产品 Features Update + 收集反馈

### 2.3 Contract Key Terms

- **期限：** 初始 3 个月，之后月度自动续，30天书面通知可终止
- **内容义务：** 每月最少 3 篇 Kuse/Junior 相关内容（X thread/YouTube/blog 不限）
- **报酬：** 月度 $200/月 + Sales commission 15%（首月+所有续费）
- **支付：** USD 账户，国际电汇，Ambassador 承担己方银行手续费
- **签约代表：** Head of Growth

### 2.4 Japan Market Notes
- 日本 KOL 特别看重公司可信度：准备好 founder LinkedIn、公司成立时间、用户数
- Demo 话术需日语版
- 日本大使独立 Slack channel 用日语沟通

---

## 3. SEO & Backlink

### 3.1 Backlink Comment Tool (Chrome Extension)
- **Repo:** github.com/haoylai11-dotcom/backlink-tool
- **依赖：** Ahrefs API key + LLM API
- **流程：**
  1. Chrome 开发者模式 → 加载扩展
  2. Settings: 填 Ahrefs API Key + Min DR (默认 10) + LLM API + 评论身份
  3. Dashboard: 输入目标域名 → Scrape（按 DR 降序）
  4. Detect Comments → 检测可评论页面
  5. Generate AI → AI 生成定制评论
  6. Post All → 自动提交
- 发布前人工检查；控制频率避免封 IP

### 3.2 Backlink Pilot (Node.js CLI)
- **Repo:** github.com/s87343472/backlink-pilot
- 批量提交网站到 259 个目录站/startup 平台
- `node src/cli.js start` 开始，`node src/cli.js status` 查进度
- `tail -f logs/submit.log` 实时看日志

### 3.3 Tool Comparison
| | Backlink Comment Tool | Backlink Pilot |
|---|---|---|
| 形态 | Chrome 扩展 | Node.js CLI |
| 策略 | 竞品反链页面评论 | 目录站批量提交 |
| 目标 | 精准高 DR 页面 | 广撒网 259 站 |
| 依赖 | Ahrefs API (付费) | 免费 |
| 适合 | 精细化 SEO | 新站快速铺量 |

### 3.4 Keywords Research Playbook
1. 罗列产品 features/values/宣传资料 → AI 生成第一轮 brainstorming（这轮只是方向参考，不可直接用）
2. 竞品关键词调研：Semrush/Ahrefs API 下载竞品全部 keyword list → 上传 LLM → 生成 keyword clusters → 看分布
3. 找到目标 cluster（如产品导向的）→ LLM 进一步输出 top 30 keywords
4. 留下的关键词基本可用
5. Google Search More + Google Trends 补充：Volume 暂时不大但持续上升的词值得做，竞争小排名容易
6. 回到第一步的 brainstorm 核心词做发散：如 "ai essay writer" 核心是 essay → 试 "essay + builder/ai/generator" 等 → Keyword Magic Tool 给发散词

### 3.5 DR 提升策略
- Guest posts + 产品目录提交 → 目标 DR 10→15（约4周）
- Backlink Comment Tool 做评论外链补充
- Ahrefs 监控竞品反链动态

---

## 4. YouTube Campaign Management

### 4.1 KOL Tier Pricing Reference
| Tier | 粉丝数 | 单条报价 |
|------|--------|----------|
| Micro | 10K-50K | $200-$800 |
| Mid-tier | 50K-200K | $800-$2,500 |
| Large | 200K+ | $2,500+ |

### 4.2 Budget Allocation ($30K example)
- Kuse: $20K (67%) — 个人产品需要更大 awareness
- Junior: $10K (33%) — toB 更看重精准
- 按市场：US 25% / Japan 25% / Korea 25% / Brazil 10% / Others 15%

### 4.3 Market Priority
| 市场 | 密度 | 备注 |
|------|------|------|
| 🇯🇵 日本 | 最高 | AI 工具频道密集，大使计划已建立，竞争小 ROI 高 |
| 🇺🇸 英语 | 高 | 最大市场，竞争最激烈 |
| 🇰🇷 韩国 | 中 | AI 热度高但市场较小 |
| 🇧🇷 巴西 | 中低 | 葡语有潜力但 KOL 少 |
| 🇵🇱 波兰 | 低 | 需 Google search scraper 发掘，本地语言播粉比高 |

---

## 5. X/Twitter Outreach

### 5.1 KOL Classification
| Category | 特征 | 策略 |
|----------|------|------|
| Cat 1: 一言九鼎型 | 真实 builder/VC/senior eng | 产品体验 → 自发推荐 |
| Cat 2: 传播力型 | 大 reach，内容还行 | 付费合作，awareness |
| Cat 3: 聚合型 | 转发为主，广告多 | 跳过 |

### 5.2 Outreach Hygiene
- 验证 handle：确认是本人（@t3dotgg ≠ Theo 的案例）
- 去重：同一人可能多平台账号（如 Chubby = @kimmonismus）
- 竞品检查：确认是否已推广直接竞品
- 受众地理：X 粉丝地理分布可能与预期不同（如印度占比高）

---

## 6. Landing Page Design

1. 想好 H1 设计（整体不超过 H3），划分 section
2. 找竞对 Page section 参考（pollo.ai / manus.im / flowith.io / affine）
3. 根据 section 写好内容制作表格
   - 参考: Lark `E0fxwsdCiiWqAHkZNk4l5uM4gkc` (Excel Landing Page)
   - 参考: Lark `D5sewucg9iZnrlkVdGPlQQHLgzg` (Open Cowork Landing)
4. 将表格发给 Jieying Yang 沟通需求和页面，制作上线

---

## 7. Ad Accounts (Official)

### X (@hirejuniorso)
- Login: Google → support@junior.so / Junior2026!
- 购买 Premium

### YouTube Ads
- Login: Google → support@junior.so / Junior2026!
- ads.google.com → Sign in（前置信息已填，注意实际付费金额）

### LinkedIn
- Login: Google → haoylai11@gmail.com / xjy20041111
- 需手机验证（找 Jiayu）

---

## 8. Data Collection Pipeline (Technical)

See `references/apify-workarounds.md` for Apify quirks and fallbacks.

### Method A: Apify Channel Scraper (ASCII handles only)
```bash
curl -s "https://api.apify.com/v2/acts/streamers~youtube-channel-scraper/runs" \
  -X POST -H "Authorization: Bearer $(cat .apify_key)" \
  -H "Content-Type: application/json" \
  -d '{"startUrls":[{"url":"https://www.youtube.com/@handle"}]}'
```

### Method B: curl + HTML (universal, recommended)
```bash
html=$(curl -s -L "https://www.youtube.com/@handle/about" \
  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36" \
  -H "Accept-Language: ja-JP,ja;q=0.9,en;q=0.5" --max-time 15)
# Subs: grep -oP 'チャンネル登録者数 [^"]*'
# Views: grep -oP '"viewCountText":\{"simpleText":"[^"]*"' | head -8
# Dates: grep -oP '"publishedTimeText":\{"simpleText":"[^"]*"' | head -6
```

### Method C: Non-English market discovery
Google search scraper → `site:youtube.com` + target language keywords → oEmbed API to map video→channel:
```
GET https://www.youtube.com/oembed?url=https://www.youtube.com/watch?v={VIDEO_ID}&format=json
```

---

## 9. Decision Quick Reference

| 问题 | 答案 |
|------|------|
| KOL 报价太贵？ | 看 CPM 不看绝对价格。$8000 CPM $41 比 $800 CPM $274 值 |
| 选 Kuse 还是 Junior？ | 受众是个人 → Kuse；团队/企业主 → Junior |
| 日本 vs 英语？ | 日本 KOL 密度高竞争小，同预算 ROI 更高 |
| 播粉比异常高？ | 检查是否新号（<6月）或 Shorts 冲量 |
| Ambassador vs 一次性？ | 长期($200/月+15%)比单次($2000+)划算，前提 KOL 真活跃 |
| 爆款内容规律？ | 实测+"XX分钟学会"标题；热点工具首发(3-7天窗口)；A vs B 对比 |

---

## 10. Key Documents Index

| 文档 | 路径/链接 | 内容 |
|------|----------|------|
| Ambassador Program | `archives/2026-03-20-ambassador-program.md` | 三级体系 |
| Ambassador 合同模板 | `archives/2026-03-28-kol-ambassador-agreement-nakashima.md` | 日英双语 |
| Campaign Brief V2 | `archives/agency-kol-brief-v2.md` | YouTube Campaign brief |
| JP Ambassador Program | Lark `L5R9wwKsOivCYek1F6alqvIBgfh` (EN) / `HgNewLssdixHObkcimVlsCoVg4d` (JP) | |
| Ambassador 工作明细 | Lark `M3Ykwkpnmia5MqkecRUlPE1egOt` | 合同模板 |
| 讲稿参考 | Lark `Z9AGwkWrniOwPmkjyAileA8BgPb` | 3.26 JP Ambassador |
| PPT | Figma `c2vLpDbyN5T0PizEzV4ZrU` | Kuse for Japan KOLs |
| Backlink Tool Guide | `archives/backlink-comment-tool-guide.md` | Chrome 扩展使用 |
| KOL Top 30 | `archives/kol-top30-final-20260327.md` | 最终名单 |
| Landing Page Excel | Lark `E0fxwsdCiiWqAHkZNk4l5uM4gkc` | |
| 已分析频道记录 | `references/analyzed-channels.md` | 35+ 频道 top picks |
| Apify 踩坑 | `references/apify-workarounds.md` | 技术 workarounds |
