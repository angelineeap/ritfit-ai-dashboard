# RITFIT Marketing AI — Full Family Tree

```
EMOJI LEGEND
🤖 Skill / Agent       📁 Knowledge         🛠️ Tools
⏰ Scheduled / Cron    👤 Human handoff     🔗 Chain
✅ Live   ⏳ In progress   — Planned
```

```
RITFIT Marketing AI System
│
├── 🏠 Context Files (Foundation) — every agent reads these
│   ├── 📄 brand-context.md
│   ├── 📄 brand-voice.md
│   ├── 📄 product-offering.md
│   ├── 📄 brand-visual-guidelines.md
│   ├── 📄 ip-exposure-checklist.md
│   └── 📄 ritfit-running-context.md
│
├── 🧠 Bob — Architect, coordinator, maintenance
│   ├── 🤖 cherry-agent-onboarding ✅ v3.1.0
│   │   └── 🛠️ Lark Base
│   ├── 🤖 cherry-agents-relink ✅ v2.2.0
│   │   └── 🛠️ Lark Base · Lark Mail
│   ├── 🤖 cherry-cleanup ✅ v2.0.0
│   │   └── 🛠️ JDY · Lark Base · Lark Docs
│   ├── 🤖 ritfit-ai-dashboard ✅ v4.4.0
│   │   ├── 📁 Visual Guidelines · IP Checklist
│   │   └── 🛠️ JDY · GERP · Canva · Bitly · Shopify · Lark Base · Lark Mail · Web Scraping
│   ├── 🤖 ritfit-github-skill-maker ✅ v2.0.0
│   │   └── 🛠️ Lark Base
│   ├── 🤖 ritfit-stress-test ✅ v1.0.0
│   ├── ⏰ Scheduled: monthly (1st, 10:00)
│   └── 🛠️ Shared toolkit (22) — lark-* · feishu-* · find-skills · skill-creator
│
├── ⚙️ Cinnamon — General ops — adcode, bitly, KOL follow-up, payment
│   ├── 🤖 angel-okr ✅
│   ├── 🤖 ritfit-adcode ✅ v3.4.0
│   │   ├── 📁 Running Context
│   │   ├── 🛠️ JDY · Bitly · Lark Base · Lark Mail
│   │   ├── 🔗 → post-register
│   │   └── 👤 human reviews
│   ├── 🤖 ritfit-bitly-code ✅ v3.6.0
│   │   ├── 📁 Product Catalogue
│   │   ├── 🛠️ JDY · Bitly · Shopify · Lark Base
│   │   └── also on Lulu
│   ├── 🤖 ritfit-campaign-planner ✅
│   │   └── 📁 Brand Context · Brand Voice · Product Catalogue · Running Context
│   ├── 🤖 ritfit-campaign-recap ✅ v2.1.1
│   │   └── 🛠️ Lark Docs
│   ├── 🤖 ritfit-contract-maker ✅ v16.11.0
│   │   ├── 🛠️ JDY · Lark Base · Lark Mail · Lark Docs
│   │   ├── 🔗 → new-collab · email-reply
│   │   └── 👤 human reviews · also on Tracey
│   ├── 🤖 ritfit-email-reply ✅ v6.11.0
│   │   ├── 📁 Running Context · Product Catalogue
│   │   ├── 🛠️ JDY · Bitly · Lark Base · Lark Mail
│   │   ├── 🔗 → contract-maker ⏳
│   │   └── 👤 human reviews · also on Lulu, Tracey
│   ├── 🤖 ritfit-email-template-maker ✅
│   ├── 🧩 ritfit-gerp-read ✅
│   │   ├── 🧩 Supporting — Reads GERP for inventory and warehouse state
│   │   ├── 🛠️ JDY · GERP
│   │   └── also on Tracey
│   ├── 🤖 ritfit-kol-approach ✅ v1.2.0
│   │   ├── 📁 Running Context
│   │   └── 🛠️ Lark Base · Lark Mail
│   ├── 🤖 ritfit-kol-follow-up ✅ v1.8.2
│   │   ├── 📁 Running Context
│   │   ├── 🛠️ JDY · Bitly · Lark Base · Lark Mail
│   │   └── 🔗 → bitly-code
│   ├── 🤖 ritfit-kol-register ✅ v1.0.0
│   │   ├── 📁 Running Context
│   │   ├── 🛠️ Bitly · Lark Base
│   │   └── 🔗 → kol-approach
│   ├── 🧩 ritfit-lark-hardcode-fallback ✅ v1.0.0
│   │   ├── 🧩 Supporting — Shared lookup table — Base IDs and tokens for every Feishu skill
│   │   ├── 🛠️ Lark Base
│   │   └── also on Lulu, Scooby, Tracey
│   ├── 🤖 ritfit-payment ✅ v2.0.2
│   │   ├── 🛠️ JDY · Lark Base · Lark Mail
│   │   └── 👤 human reviews
│   ├── 🤖 ritfit-post-register ✅ v3.0.0
│   │   ├── 📁 Running Context
│   │   └── 🛠️ Bitly · Lark Base
│   ├── 🤖 ritfit-product-launch-planner ✅
│   │   ├── 📁 Brand Context · Brand Voice · Product Catalogue
│   │   └── 🛠️ Bitly
│   ├── 🤖 ritfit-showroom-manager ✅ v1.1.0
│   │   ├── 🛠️ Lark Base
│   │   └── also on Tracey
│   ├── ⏰ Scheduled: every 3 days (09:30) · every 3 days (10:00) · every 3 days (09:30) · weekly (Mon 09:30)
│   └── 🛠️ Shared toolkit (23) — lark-* · feishu-* · find-skills · skill-creator
│
├── 📧 Lulu — KOL email replies
│   ├── 🤖 ritfit-bitly-code ✅ v3.6.0
│   │   ├── 📁 Product Catalogue
│   │   ├── 🛠️ JDY · Bitly · Shopify · Lark Base
│   │   └── also on Cinnamon
│   ├── 🤖 ritfit-email-reply ✅ v6.11.0
│   │   ├── 📁 Running Context · Product Catalogue
│   │   ├── 🛠️ JDY · Bitly · Lark Base · Lark Mail
│   │   ├── 🔗 → contract-maker ⏳
│   │   └── 👤 human reviews · also on Cinnamon, Tracey
│   ├── 🧩 ritfit-jdy-read ✅
│   │   ├── 🧩 Supporting — Reads JDY records other skills build on
│   │   ├── 🛠️ JDY · GERP · Lark Base
│   │   └── also on Tracey
│   ├── 🧩 ritfit-lark-hardcode-fallback ✅ v1.0.0
│   │   ├── 🧩 Supporting — Shared lookup table — Base IDs and tokens for every Feishu skill
│   │   ├── 🛠️ Lark Base
│   │   └── also on Cinnamon, Scooby, Tracey
│   ├── ⏰ Scheduled: daily (09:10, weekdays)
│   └── 🛠️ Shared toolkit (23) — lark-* · feishu-* · find-skills · skill-creator
│
├── ✍️ Scooby — Content creation
│   ├── 🤖 ritfit-content ✅
│   │   ├── 📁 Brand Voice · Brand Context · Product Catalogue · Running Context
│   │   └── 🛠️ Shopify · Lark Base · Lark Docs
│   ├── 🤖 ritfit-content-idea-register ✅ v2.7.0
│   │   ├── 🛠️ Lark Base · Web Scraping
│   │   └── 🔗 → scraping
│   ├── 🧩 ritfit-lark-hardcode-fallback ✅ v1.0.0
│   │   ├── 🧩 Supporting — Shared lookup table — Base IDs and tokens for every Feishu skill
│   │   ├── 🛠️ Lark Base
│   │   └── also on Cinnamon, Lulu, Tracey
│   ├── 🧩 ritfit-scraping ✅ v1.3.0
│   │   ├── 🧩 Supporting — Shared browser capability — reads the page another skill needs
│   │   ├── 🛠️ Web Scraping
│   │   └── also on Spy
│   ├── ⏰ Scheduled: weekdays (16:00)
│   └── 🛠️ Shared toolkit (23) — lark-* · feishu-* · find-skills · skill-creator
│
├── 🕵️ Spy — Competitor + Facebook group intelligence
│   ├── 🤖 ritfit-competitor-stalk ✅ v1.8.0
│   │   ├── 🛠️ Web Scraping
│   │   └── 🔗 → scraping
│   ├── 🤖 ritfit-fb-stalk ✅ v1.0.0
│   │   ├── 🛠️ Lark Base · Lark Docs · Web Scraping
│   │   └── 🔗 → scraping
│   ├── 🧩 ritfit-scraping ✅ v1.3.0
│   │   ├── 🧩 Supporting — Shared browser capability — reads the page another skill needs
│   │   ├── 🛠️ Web Scraping
│   │   └── also on Scooby
│   └── 🛠️ Shared toolkit (22) — lark-* · feishu-* · find-skills · skill-creator
│
└── 📦 Tracey — KOL contracts, orders, shipment tracking
    ├── 🤖 ritfit-contract-maker ✅ v16.11.0
    │   ├── 🛠️ JDY · Lark Base · Lark Mail · Lark Docs
    │   ├── 🔗 → new-collab · email-reply
    │   └── 👤 human reviews · also on Cinnamon
    ├── 🤖 ritfit-email-reply ✅ v6.11.0
    │   ├── 📁 Running Context · Product Catalogue
    │   ├── 🛠️ JDY · Bitly · Lark Base · Lark Mail
    │   ├── 🔗 → contract-maker ⏳
    │   └── 👤 human reviews · also on Cinnamon, Lulu
    ├── 🧩 ritfit-gerp-read ✅
    │   ├── 🧩 Supporting — Reads GERP for inventory and warehouse state
    │   ├── 🛠️ JDY · GERP
    │   └── also on Cinnamon
    ├── 🧩 ritfit-jdy-read ✅
    │   ├── 🧩 Supporting — Reads JDY records other skills build on
    │   ├── 🛠️ JDY · GERP · Lark Base
    │   └── also on Lulu
    ├── 🧩 ritfit-lark-hardcode-fallback ✅ v1.0.0
    │   ├── 🧩 Supporting — Shared lookup table — Base IDs and tokens for every Feishu skill
    │   ├── 🛠️ Lark Base
    │   └── also on Cinnamon, Lulu, Scooby
    ├── 🤖 ritfit-new-collab ✅ v4.1.0
    │   └── 🛠️ JDY · Bitly · Lark Base · Lark Docs
    ├── 🤖 ritfit-new-order-draft ✅ v1.25.0
    │   ├── 🛠️ JDY · GERP · Lark Base
    │   └── 🔗 → new-order-submit
    ├── 🤖 ritfit-new-order-submit ✅ v1.15.0
    │   └── 🛠️ JDY · GERP · Lark Base
    ├── 🤖 ritfit-showroom-manager ✅ v1.1.0
    │   ├── 🛠️ Lark Base
    │   └── also on Cinnamon
    ├── 🤖 ritfit-tracking-JDY ✅
    │   ├── 🛠️ JDY · GERP · Lark Base · Lark Mail
    │   └── 👤 human reviews
    ├── ⏰ Scheduled: daily (09:30)
    └── 🛠️ Shared toolkit (22) — lark-* · feishu-* · find-skills · skill-creator
│
└── 🔗 Cross-skill chains
    ├── ritfit-email-reply → ritfit-contract-maker ⏳ not wired
    ├── ritfit-contract-maker → ritfit-new-collab ✅
    ├── ritfit-contract-maker → ritfit-email-reply ✅
    ├── ritfit-kol-register → ritfit-kol-approach ✅
    ├── ritfit-kol-search → ritfit-kol-approach ⏳ not wired
    ├── ritfit-adcode → ritfit-post-register ✅
    ├── ritfit-new-order-draft → ritfit-new-order-submit ✅
    ├── ritfit-kol-follow-up → ritfit-bitly-code ✅
    ├── ritfit-content-idea-register → ritfit-scraping ✅
    ├── ritfit-competitor-stalk → ritfit-scraping ✅
    └── ritfit-fb-stalk → ritfit-scraping ✅
```