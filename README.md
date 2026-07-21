### Hi, I'm Ángel 👋

I build data pipelines that turn messy, unstructured websites into clean, structured datasets — end to end, from extraction to delivery.

**Core stack:**

- 🐍 **Python** — async-first architecture, not just scripts
- ⚡ **Async Ingestion** — Playwright + HTTPX for JS-rendered sites, API interception, and stealth session handling
- 🐼 **Pandas / NumPy** — schema enforcement, deduplication, incremental data merging
- 🗄️ **SQL / PostgreSQL** — structured storage for pipelines that need to scale past flat files
- 🔁 **Automated ETL** — config-driven pipelines that adapt to new sources without rewriting code

---

**What I actually build:**

Most scraping scripts break the moment a site changes its layout, throttles requests, or loads content dynamically. I build pipelines designed to survive that:

- Schema-driven extraction — one config file per domain, zero hardcoded logic per site
- Concurrency-controlled async workers (semaphore-managed, not naive parallel requests)
- Incremental merge + dedup layers so re-running a pipeline never duplicates data
- Stealth session handling for JS-heavy / bot-protected targets
- Bronze → Silver data layering: raw cache first, validated structured output second

---

**Currently working on:**  
🔧 A modular, config-driven web scraping engine — swap in a new target site by editing a schema, not the pipeline code.

📫 Reach me: [angeldeangelis1@gmail.com](mailto:angeldeangelis1@gmail.com) / [Upwork Profile](https://www.upwork.com/freelancers/~015591486ae29424db)
