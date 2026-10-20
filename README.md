# Case studies — Arsen Zakaryan

AI automation and business systems I built for real clients and run in production. The client code is private, so each project is shown through a write-up, architecture diagrams, real screenshots and a short animated walkthrough. Every number on these pages comes from the project's repository, test runs or git history.

I design the systems, make the architecture decisions and run them in production; the code is written by AI coding agents I direct (mainly Claude Code).

| | Project | Key result |
|---|---|---|
| <a href="cbs-sales-assistant/"><img src="media/cbs/cbs-flow.gif" width="260" alt="CBS sales assistant"></a> | **[AI sales assistant — CBS Construction](cbs-sales-assistant/)**<br/>Multilingual (hy/ru/en) n8n + Gemini agent over a pgvector catalogue of 397 apartments and parking spaces; leads go to Telegram and Sheets. | Must look prices up before quoting: retrieval **3/6 → 12/12**, **14/14** quoted figures real. A failed nightly sync can no longer empty the catalogue. |
| <a href="oil-station-platform/"><img src="media/oil/oil-flow.gif" width="260" alt="Oil station platform"></a> | **[Oil-change station platform — Har Oil](oil-station-platform/)**<br/>Stock, services, sales, cash and debts for a live station: web app, Telegram bot, Mini App, Windows label-print agent. | Live, in daily use. **1,020 automated tests** gate every deploy; audit log protected by database triggers. |
| <a href="carstar-pricing-engine/"><img src="media/carstar/carstar-flow.gif" width="260" alt="carstar pricing engine"></a> | **[Vehicle import pricing engine — carstar.am](carstar-pricing-engine/)**<br/>US auction price → landed cost in Armenia: fees, three shipping legs, customs, Central Bank rates. | Armenia's customs rules rebuilt as a local engine with fallbacks; itemized quote in one request. **860+ commits.** |
| <a href="cleanwhale-internal-ai/"><img src="media/cleanwhale/cleanwhale-flow.gif" width="260" alt="CleanWhale"></a> | **[QA monitor and staff assistant — CleanWhale](cleanwhale-internal-ai/)**<br/>66 Playwright tests on the live booking site every 6 hours; a Gemini Telegram assistant on Cloud Run. | Suite calibrated on **5 real bugs** on the live site; failures arrive as a screenshot with the broken element outlined. |

**Contact:** arsen.zakaryan@gmail.com · [github.com/zakarars](https://github.com/zakarars) · [LinkedIn](https://www.linkedin.com/in/arsen-zakaryan-964968133)
