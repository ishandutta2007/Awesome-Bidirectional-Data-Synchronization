# Awesome-Bidirectional-Data-Synchronization

# Awesome-Bidirectional-Data-Synchronization

**Top Bidirectional Data Synchronization (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Reverse ETL, iPaaS, CRM Sync & Warehouse-to-App Activation*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Bidirectional Data Synchronization**. These tools enable organizations to keep data consistent across CRMs, warehouses, and business applications—from fully managed reverse ETL platforms with visual mapping to self-hosted integration engines and CLI-driven sync tools that give teams complete control over their data pipelines and transformation logic.



**Examples** include Hightouch, Census, Fivetran, Workato, MuleSoft, Celigo, Zapier, Make, Syncari, and HubSpot Data Sync (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted reverse ETL, CRM sync, and open integration infrastructure. **Critical note**: The open-source landscape is fragmented—**PyReverseETL** and **drt** are CLI-first reverse ETL tools, **CRMSYNC** handles HubSpot/Pipedrive bidirectional sync, **Cenit IO** is a full iPaaS, and **ETLX** offers SQL-first pipeline definition. No open-source project matches Hightouch's visual modeling or Fivetran's 500+ managed connectors.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global data integration, iPaaS, and Reverse ETL sector represents an estimated market size of **$10B–$15B+** (with iPaaS pegged at ~$8B–$15B and Reverse ETL / Data Activation at ~$2.8B–$3.5B, both compounding at >20% CAGR through 2026). The market exhibits a **moderately fragmented, bifurcated structure**: the enterprise tier is heavily concentrated among incumbent giants (Salesforce/MuleSoft, Celonis, Workato) creating deep ecosystem moats, while the mid-market, SMB, and reverse ETL tiers remain competitive and fragmented with modern composable CDP and AI-orchestrated automation tools.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits | Description & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[HubSpot Data Sync](https://www.hubspot.com/)** | **~$21B–$36B Valuation** / ~$3.1B ARR | Starts at **$20/seat/month** (Data Hub Starter) | **Free forever plan**: Unlimited two-way sync on 100+ native apps capped at default field mappings only (up to 2 users; custom mappings require Starter). 14-day free trial on higher tiers. | Native bidirectional sync between HubSpot and Salesforce, NetSuite, and other systems. Best for HubSpot users needing CRM sync. |
| **[Make](https://www.make.com/)** | **~$11B–$13B Valuation** (via parent Celonis; ~$52M–$100M ARR) | Starts at **$9/month** (Core plan, 10,000 credits/mo, billed annually) | **Free forever plan**: 1,000 credits/month, max 2 active scenarios, minimum 15-minute sync interval. | Visual automation platform with webhook support and 1,000+ connectors. Best for power users wanting visual flows with more control than Zapier. |
| **[MuleSoft](https://www.mulesoft.com/)** (Salesforce) | **~$6.5B Acquired Valuation** (Salesforce Integration segment ~$5.8B ARR) | Starts at **$2,000/month** (MuleSoft Integration & Automation Starter) | **30-day free trial**: Full access to Anypoint Platform evaluation; no permanent free tier. | Enterprise integration platform with API-led connectivity and Anypoint Platform. Best for large enterprises with complex API ecosystems. |
| **[Workato](https://www.workato.com/)** | **~$5.7B Valuation** / ~$150M ARR | Starts at **$75/month** (Workato Pro base) up to custom enterprise contracts | **Evaluation plan**: One-time grant of 50,000 non-refreshing Workato credits; enterprise proofs-of-concept available via sales. | Enterprise iPaaS with recipe-based automation and bidirectional sync across 1,000+ apps. Best for enterprises needing governed integration. |
| **[Fivetran](https://www.fivetran.com/)** | **~$5.6B Valuation** / ~$325M ARR | Consumption-based starting at **~$500/month** (Standard plan per 1M MAR baseline) | **Free forever plan**: 500,000 Monthly Active Rows (MAR) for ELT, 3,500 MAR for Activations (Reverse ETL), 5,000 model runs/month. Plus 14-day free trial per new connection. | Automated data integration with 500+ connectors for ELT pipelines and Reverse ETL activations. Best for managed warehouse ingestion and syncs. |
| **[Zapier](https://zapier.com/)** | **~$5.0B Valuation** / ~$310M–$400M ARR | Starts at **$19.99/month** (Professional plan, 750 tasks/mo, billed annually) | **Free forever plan**: 100 tasks/month, 2-step Zaps only (1 trigger, 1 action), 15-minute polling interval, standard apps only. 14-day Pro trial on signup. | No-code automation with 7,000+ app connectors and webhook triggers. Best for non-technical teams wanting trigger-action syncs. |
| **[Hightouch](https://hightouch.com/)** | **~$2.75B Valuation** / ~$100M ARR | Starts at **$350/month** (Starter tier for reverse ETL syncs) | **Free forever plan**: Up to 2 active syncs/month, hourly sync frequency limit, unlimited destinations, and unlimited seats. | Composable CDP and Reverse ETL platform syncing warehouse data to 200+ destinations. Best for data teams activating warehouse data into CRMs. |
| **[Census](https://www.getcensus.com/)** (Fivetran Activations) | **Acquired by Fivetran** (~$5.6B combined parent valuation) | Consumption-based starting at **~$350–$500/month** (via Fivetran Activations consumption) | **Free tier via Fivetran**: 3,500 activation Monthly Active Rows (MAR)/month on Free tier. 14-day free trial on new activation syncs. | Reverse ETL and operational analytics platform with visual mapping. Best for teams wanting mature reverse ETL with strong dbt integration. |
| **[Celigo](https://www.celigo.com/)** | **~$100M+ ARR** / ~$80M Total Funding | Starts at **$600/month** (Standard tier, billed annually) | **30-day free trial** with full platform access; transitions to Free plan limited to 2 endpoints and 1 active flow. | Integration platform with pre-built connectors for NetSuite, Salesforce, and eCommerce. Best for NetSuite-centric finance & commerce workflows. |
| **[Syncari](https://syncari.com/)** | **~$100M–$250M Est. Valuation** / ~$2M–$5M ARR | Starts at **$995/month** (Starter tier) | **30-day free trial** (Test Drive) with full schema studio & multi-directional sync access; no permanent free tier (base starter plan limits to 1 synapse and 100k records). | Revenue operations data sync with bidirectional sync and conflict resolution across CRM, marketing, and finance. Best for RevOps teams. |

## Open-Source GitHub Projects



- **[PyReverseETL](https://pypi.org/project/PyReverseETL/)**

  **Reverse ETL engine with Rust core and Python API** (license per PyPI) — **the most technically ambitious open-source reverse ETL tool** found in this research, with a compiled Rust engine and honest status reporting . **Features**: **PostgreSQL/MySQL/S3 sources** verified against real services; **webhook destination** verified end-to-end; **CRM/marketing adapters** (mock-verified); **PII masking compliance rules** before data leaves the process; **lineage tracking** across runs; CLI commands (`create-workflow`, `create-activation`, `execute`) and Python API (`run_sync`). Explicitly documents what is tested, untested, or broken in `ROADMAP_HONEST.md` . **Tech stack**: Rust (core, via PyO3), Python (API/CLI). **Deploy**: `pip install pyreverseetl`. **Trade-off**: **Beta (v3.1.4)**—CRM/marketing adapters are mock-verified only, not live-tested. Several modules remain unwired. GCS/Azure, Kafka, CDC streaming are not implemented. **Best for**: data engineers wanting a real, honest reverse ETL engine with PII masking and lineage—willing to accept beta status and verify CRM connectors before production use.



- **[drt (data reverse tool)](https://pypi.org/project/drt-core/)**

  **CLI-first reverse ETL for the code-first data stack** (license per PyPI) — **the most developer-friendly open-source Census/Hightouch alternative**, designed as the reverse leg of dbt/dlt . **Features**: **YAML sync definitions**—Git-native, CI/CD-friendly; **sources**: BigQuery, DuckDB, PostgreSQL (v0.1); **destinations**: REST API, Slack webhook, GitHub Actions, **HubSpot (Contacts/Deals/Companies)** verified in v0.1; **dry-run** preview before writing; MCP server planned (v0.3); Dagster/Airflow integration planned . **Tech stack**: Python (CLI). **Deploy**: `pip install drt-core[bigquery]`; `drt init`, `drt run`. **Trade-off**: **v0.1 maturity**—Snowflake, Redshift, MySQL sources are planned, not shipped. Salesforce, Notion, Google Sheets destinations are planned. Incremental sync and retry logic are v0.2 roadmap items. **Best for**: dbt-centric data teams wanting a Git-native reverse ETL CLI with HubSpot sync already working—without per-row SaaS pricing.



- **[CRMSYNC](https://github.com/cognis-digital/crmsync)**

  **Bidirectional, idempotent CRM sync between SQLite and HubSpot/Pipedrive/Salesforce** (license per repo) — **the most focused open-source bidirectional sync tool** for CRM data . **Features**: **`diff` command** shows drift between a versioned CRM export (CSV/TSV/JSON) and local SQLite, exits 1 if drift found—**CI-gateable**; **`apply` command** syncs DB to match export idempotently; **MCP-native**—agents can drive it; single-purpose, scriptable, self-hostable. No $20k iPaaS contract required . **Tech stack**: Python (pip install). **Deploy**: `pip install cognis-crmsync`; CLI. **Trade-off**: **SQLite source-of-truth model**—it makes your CRM a replica of a local file, not a real-time API-to-API sync. The "bidirectional" aspect is achieved through diff/apply cycles, not continuous streaming. CRM adapters are mock-verified (per PyReverseETL-style honesty). **Best for**: teams wanting CI-enforced CRM consistency and drift detection without an iPaaS—especially those with existing versioned CRM exports or agent-driven workflows.



- **[Cenit IO](https://github.com/cenit-io/cenit)**

  **100% open-source integration platform (iPaaS)** (Ruby, ~502 stars) — **the most complete open-source iPaaS** for building bidirectional data flows . **Features**: Automates repetitive manual operations; connects tools into repeatable flows; supports multitenant and on-premises deployment; backed-less data-flow architecture . **Tech stack**: Ruby. **Deploy**: Self-hosted. **Trade-off**: **Medium production readiness**—suitable for prototypes or internal workflows, but requires dependency and maintenance checks before production. Integration path is not obvious from metadata; validate setup cost before committing . **Best for**: teams wanting a self-hosted iPaaS foundation for internal workflows—with awareness that it requires proof-of-concept validation before production.



- **[ETLX](https://pkg.go.dev/github.com/realdatadriven/etlx)**

  **SQL-first data workflow engine with self-documenting pipelines** (Apache 2.0) — **the most philosophically rigorous open-source pipeline specification** . **Features**: Pipelines defined in **structured Markdown + YAML + SQL**—the pipeline **is** the documentation and governance artifact; executes ETL/ELT/**Reverse ETL**, data quality, report generation, and automation; runs on **DuckDB, PostgreSQL, SQLite, MySQL, SQL Server, ODBC**; available as CLI and embeddable Go library . **Tech stack**: Go (DuckDB-powered, not locked to it). **Deploy**: `etlx --config pipeline.md`. **Trade-off**: **Specification and runtime, not a turnkey connector library**—you write the SQL and YAML; it executes. No pre-built CRM adapters. **Best for**: data engineers wanting explicit, inspectable, versionable data workflows where the pipeline file itself is the source of truth.



- **[FlowForge](https://github.com/DeveloperSarim/FlowForge)**

  **Self-hosted n8n/Zapier alternative for PHP shared hosting** (AGPL-3.0) — **the most accessible open-source automation platform for budget hosting** . **Features**: 1,690 app integrations; AI Builder for custom apps from API docs; automatic retries; AI voice agents; MCP support; runs on cPanel/Hostinger with **one cron job**; no Node.js server required . **Tech stack**: PHP, MySQL. **Deploy**: Shared hosting (cPanel/hPanel) or VPS. **Trade-off**: **Newer project with limited community validation** compared to n8n. PHP-based; not for teams needing Node.js ecosystem. **Best for**: small businesses on shared hosting wanting visual automation without managing a Node.js stack.



### Additional Strong Open-Source Options



- **Dango** — Open-source data platform for small teams (Apache 2.0). Ingestion via dlt, DuckDB warehouse, dbt transforms, Metabase dashboards. **Note**: **Explicitly no reverse ETL** (known limitation)—ingestion and transformation only . **Best for**: small teams wanting a local-first data stack without reverse ETL needs.

- **Activepieces** — Open-source Zapier alternative (MIT). 500+ integrations, visual builder, self-hosted. **Note**: **Automation platform, not reverse ETL**—connects apps but does not sync warehouse data to destinations . **Best for**: teams wanting a self-hosted automation platform with permissive licensing.

- **CloudQuery** — Open-source data movement tool (Go). Syncs from any source to any destination; strong for cloud infrastructure data. **Note**: **Infrastructure/security data focus**, not CRM reverse ETL . **Best for**: CSPM and cloud asset inventory pipelines.



**Frameworks for building custom systems**: Combine **PyReverseETL** for real reverse ETL with PII masking and lineage, **drt** for Git-native CLI sync to HubSpot and REST APIs, **CRMSYNC** for CI-gated CRM consistency, and **Cenit IO** or **FlowForge** for broader iPaaS workflows—creating a bidirectional sync stack. **None of these match Hightouch's visual modeling or Fivetran's managed connector breadth**; those require commercial platforms or significant connector development.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data synchronization platforms handling business data and credentials must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for connected systems.

- **The "reverse ETL" vs. "iPaaS" vs. "CRM sync" vs. "pipeline specification" distinction is critical.** **Hightouch and Census** are **reverse ETL**—they sync warehouse data to business apps. **Fivetran** is **ELT**—it ingests data into warehouses, not out. **Workato, MuleSoft, Celigo, Zapier, Make, and Syncari** are **iPaaS/automation**—they connect apps bidirectionally. **PyReverseETL and drt** are **open-source reverse ETL**. **CRMSYNC** is **CRM-specific bidirectional sync**. **Cenit IO and FlowForge** are **open-source iPaaS**. **ETLX** is a **pipeline specification**. **Choose based on whether you need warehouse-to-app sync, app-to-app integration, or pipeline definition.**

- **PyReverseETL is the most honest open-source reverse ETL tool**—it documents exactly what is tested, mock-verified, or broken in `ROADMAP_HONEST.md` . **The trade-off**: beta status; CRM adapters are not live-verified. **For teams wanting real reverse ETL with PII masking and lineage, it is the strongest open-source foundation.**

- **drt is the most developer-friendly reverse ETL CLI**, designed as the reverse leg of dbt/dlt . **The trade-off**: v0.1—only BigQuery, DuckDB, and PostgreSQL sources work; HubSpot is the only CRM destination. **It is the right tool for dbt teams wanting Git-native sync without SaaS pricing, but expectations should match its early stage.**

- **CRMSYNC's approach is unique**—it makes the CRM a replica of a local SQLite file via diff/apply cycles, gateable in CI . **The trade-off**: it is not real-time API-to-API sync; it is CI-enforced consistency.

- **Cenit IO has medium production readiness**—suitable for prototypes or internal workflows, not mission-critical production without validation . **FlowForge is newer but more actively targeted at budget hosting** with 1,690 integrations .

- **Pricing opacity varies.** Hightouch, Census, Fivetran, Workato, MuleSoft, Celigo, and Syncari require sales contact or usage-based estimation. Zapier, Make, and Activepieces have free tiers. **Validate with direct vendor conversations against your sync volume and destination count.**

- Self-hosted open-source solutions require proper setup, API credentials for connected systems, and ongoing maintenance. **Sync pipelines handle business-critical data**—ensure your deployment meets your organization's security standards and includes proper error handling before production use.



---



**Made for data engineers, RevOps teams, and organizations building transparent bidirectional data synchronization solutions.**

Let's make Bidirectional Data Synchronization more open, data-driven, and sync-reliable.
