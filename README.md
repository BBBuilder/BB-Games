# BB GAME WORLD
## Canonical Location: D:\CLAUDE.AI\BB GAME WORLD

> Every file in this project lives in ONE place: the `obsidian/` folder.
> The `app/` folder holds only the deployable web app.
> No duplicates. No old versions. Always current.

---

## Folder Structure

```
BB GAME WORLD/
│
├── README.md                    ← this file
│
├── app/                         ← DEPLOYABLE APP (drag to Netlify)
│   ├── index.html               ← entire BB Games app (8 games, 3 levels)
│   ├── manifest.json            ← PWA config for iOS
│   ├── sw.js                    ← service worker (offline)
│   ├── .gitignore               ← protects secrets/keystore
│   ├── .nojekyll                ← GitHub Pages config
│   ├── 404.html                 ← SPA redirect
│   ├── icon-192.svg             ← ROARY app icon
│   └── .github/workflows/
│       └── deploy.yml           ← auto-deploy on push
│
└── obsidian/                    ← ENTIRE KNOWLEDGE BASE (open in Obsidian)
    ├── CLAUDE.md                ← MASTER INDEX — always load first
    ├── CHAT_SUMMARY_V1.md       ← full history of founding session
    ├── GAME_ARCHITECTURE.md     ← 8 games + 3 levels
    ├── REVENUE_MODEL.md         ← ad math, DAU targets
    ├── MARKETING_PIPELINE.md    ← zero-budget distribution
    ├── TECH_STACK.md            ← PWA, Netlify, APK, GitHub
    ├── CEO_ORDERS.md            ← constitutional rules + storage rules
    ├── INDIA_STRATEGY.md        ← Hindi, WhatsApp, 118M children
    ├── COMPETITOR_INTEL.md      ← BabyBus, Khan Academy, HOMER, PBS
    ├── NEXT_CHAT_PROMPT.md      ← exact prompt for next session
    ├── GIT_SETUP.md             ← GitHub push instructions
    ├── REDDIT_POSTS.md          ← 3 launch posts ready to post
    ├── WHATSAPP_MESSAGES_30.md  ← 30 messages EN + Hindi
    ├── YOUTUBE_SCRIPTS.md       ← 3 Short scripts for BB to film
    ├── ZERO_BUDGET_PLAN.md      ← 30-day zero cost plan
    ├── CEO_GAMING_SKILL.md      ← /CEO Claude skill
    ├── BTW_SKILL.md             ← /btw Claude skill
    └── .obsidian/               ← Obsidian settings + graph config
```

---

## 3 Storage Locations (always keep in sync)

| # | Location | How to update |
|---|---|---|
| 1 | `D:\CLAUDE.AI\BB GAME WORLD` | Extract ZIP from Claude |
| 2 | Claude Project Files | Upload CLAUDE.md + sub-files |
| 3 | GitHub `BBBuilder/BB-Games` | Push app/ folder changes |

---

## How to Use in Next Claude Session

Copy the prompt from `obsidian/NEXT_CHAT_PROMPT.md` exactly.
Load `obsidian/CLAUDE.md` as the project file.
Claude reads the index, pulls only what is needed. Saves 90% tokens.

---

## BB's Remaining Actions
1. Drag `app/` folder to app.netlify.com/drop
2. Upload APK to Play Store developer console
3. Record 3 phone videos of child playing

*Everything else — CEO does it.*
