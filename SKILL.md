---
name: mteam-api
description: >
  This skill provides programmatic access to the mteam PT site's official OpenAPI.

  Use this skill whenever the user asks to:
  - search for torrents on mteam
  - retrieve torrent metadata or details
  - download torrents from mteam
  - perform any other action explicitly supported by the mteam OpenAPI

  This skill MUST be used instead of:
  - guessing URLs
  - scraping HTML pages
  - fabricating torrent IDs or download links

  All operations available to this skill are strictly limited to those defined in the mteam OpenAPI documentation.

  If the user mentions "mteam" and requests any operation that could plausibly be handled by the mteam OpenAPI, always prefer this skill over generic tools.
metadata:
  api-version: "v0"
  openapi-version: "3.0.1"
---

# M-Team API

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 28 resource index files
├── operations/     # 228 operation detail files
└── schemas/        # 28 schema groups, 53 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.m-team.cc/api` - Generated server url

## Authentication

Set the `x-api-key` header on every request. Read its value from the `MTEAM_API_ACCESS_TOKEN` environment variable.

## Resources

- **種子** → `references/resources/種子.md` (32 ops) - 種子相關 API
- **用戶** → `references/resources/用戶.md` (26 ops) - 用戶相關 API
- **系統** → `references/resources/系統.md` (21 ops) - 系統相關 API
- **dmm** → `references/resources/dmm.md` (21 ops) - dmm相關 API
- **論壇** → `references/resources/論壇.md` (15 ops) - 論壇相關 API
- **菠菜** → `references/resources/菠菜.md` (15 ops) - 菠菜相關 API
- **站內信** → `references/resources/站內信.md` (14 ops) - 站內信相關 API
- **求種** → `references/resources/求種.md` (11 ops) - 求種相關 API
- **片單** → `references/resources/片單.md` (11 ops) - 片單相關 API
- **字幕** → `references/resources/字幕.md` (7 ops) - 字幕相關 API
- **評論** → `references/resources/評論.md` (7 ops) - 評論相關 API
- **tracker** → `references/resources/tracker.md` (6 ops) - tracker相關 API
- **好友** → `references/resources/好友.md` (6 ops) - 好友相關 API
- **積分商店** → `references/resources/積分商店.md` (5 ops) - 積分商店相關 API
- **首頁趣味盒** → `references/resources/首頁趣味盒.md` (5 ops) - 首頁趣味盒相關 API
- **實驗室** → `references/resources/實驗室.md` (4 ops) - 實驗室相關 API
- **邀請** → `references/resources/邀請.md` (4 ops) - 邀請相關 API
- **聯盟小組** → `references/resources/聯盟小組.md` (3 ops) - 聯盟小組相關 API
- **RSS** → `references/resources/RSS.md` (3 ops) - RSS相關 API
- **首頁投票** → `references/resources/首頁投票.md` (2 ops) - 首頁投票相關 API
- **種子候選** → `references/resources/種子候選.md` (2 ops) - 種子候選相關 API
- **友情連結** → `references/resources/友情連結.md` (2 ops) - 友情連結相關 API
- **管理組信箱** → `references/resources/管理組信箱.md` (1 ops) - 管理組信箱相關 API
- **舉報** → `references/resources/舉報.md` (1 ops) - 舉報相關 API
- **首頁新聞** → `references/resources/首頁新聞.md` (1 ops) - 首頁新聞相關 API
- **導航菜單** → `references/resources/導航菜單.md` (1 ops) - 導航菜單相關 API
- **考核** → `references/resources/考核.md` (1 ops) - 考核相關 API
- **積分流水** → `references/resources/積分流水.md` (1 ops) - 積分流水相關 API
