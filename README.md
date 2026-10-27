# Awesome-Customer-Data-Management

# Awesome-Customer-Data-Management

**Top Customer Data Management (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Customer Data Platforms (CDP), Identity Resolution, Audience Segmentation & Data Activation*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Data Management**. These tools enable organizations to collect, unify, and activate customer data across touchpoints—from fully managed enterprise CDPs with AI-powered identity graphs and real-time personalization to self-hosted platforms that give teams complete control over first-party data and privacy compliance.



**Examples** include Salesforce Data Cloud, Segment, Tealium, mParticle, Treasure Data, Amperity, RudderStack, ActionIQ, Bloomreach, and Workday Customer Data Management (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every major active project for self-hosting, CDP infrastructure, and open data activation—ideal for developers, data teams, and organizations seeking transparent, vendor-independent customer data management.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Customer Data Platform (CDP) market is estimated at ~$7.5B–$9.5B in 2024–2025 and is projected to cross $10.4B–$12.8B by 2026, advancing at a CAGR of ~23%–28%. The sector is **highly fragmented** rather than winner-take-all, split between traditional packaged CDPs, enterprise CRM/cloud suites, and composable warehouse-native architectures competing across specialized industry verticals and AI-driven activation models.



## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Market Cap) | Starting Price | Free Tier / Trial Limits | Description & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Data Cloud](https://www.salesforce.com/data/)** | ~$200B+ Market Cap ($34.9B+ FY24 Rev) | $500/mo (via 100k Flex Credits min) / $60,000/yr (Data 360 Starter) | 30-day trial with standard sandbox limits (or $0 Provisioning SKU for existing CRM customers) | Enterprise customer data platform integrated with Salesforce ecosystem. Best for Salesforce customers wanting unified customer profiles across Sales, Service, and Marketing clouds. |
| **[Workday Customer Data Management](https://www.workday.com/)** | ~$50B–$55B Market Cap ($7.3B+ FY24 Rev) | ~$35 to $100 per employee/mo (billed annually, custom enterprise contract) | 30-day proof-of-concept / evaluation period via sales (no self-serve free tier) | Customer data management within Workday Financials and HCM suite. Best for enterprises wanting customer master records integrated directly into financial planning and ERP operations. |
| **[Segment](https://segment.com/)** (Twilio) | ~$40B–$47B Market Cap (Parent Twilio) | $120/mo (Team plan with 10,000 MTUs included) | Free forever: 1,000 MTUs/mo, 2 sources, 300+ integrations; 14-day free trial on Team tier | Customer data platform for collecting, cleaning, and routing data. Best for product and growth teams wanting a developer-friendly event pipeline. |
| **[Bloomreach](https://www.bloomreach.com/)** | ~$2.2B Valuation | $5,000/mo ($60,000/yr starting tier) | 14-day guided proof-of-concept sandbox via sales (no self-serve free tier) | Commerce experience platform with integrated CDP for personalization. Best for e-commerce brands wanting customer data unified with search, merchandising, and marketing. |
| **[Tealium](https://tealium.com/)** | ~$1.2B Valuation | $1,000/mo ($12,000/yr billed annually for Data Cloud Activation) | 30-day guided proof-of-concept for qualified prospects (no self-serve free tier) | Enterprise CDP and tag management platform with real-time data activation. Best for large enterprises needing governance-first data collection across web, mobile, and offline channels. |
| **[Amperity](https://amperity.com/)** | ~$1.0B Valuation | ~$16,666/mo ($200,000/yr starting tier, based on Amps compute units) | 30-day enterprise sandbox / POC on sales engagement (no self-serve free tier) | Enterprise CDP specializing in AI identity resolution and customer 360. Best for retail and consumer brands with complex, fragmented offline and online customer records. |
| **[Treasure Data](https://www.treasuredata.com/)** | ~$600M+ Valuation (Arm acquisition $600M, $234M SoftBank round) | ~$5,000/mo ($60,000/yr enterprise base contract based on profile tiers) | 30-day complimentary proof-of-concept (POC) using customer data (no self-serve free tier) | Enterprise CDP and AI data platform. Best for data-heavy enterprises needing tight alignment between customer records and machine learning/analytics workflows. |
| **[ActionIQ](https://www.actioniq.com/)** | ~$511M Valuation (Acquired by Uniphore) | ~$8,333/mo ($100,000/yr starting tier) | 30-day guided POC / staging deployment (no self-serve free tier) | Enterprise CDP focused on marketing activation and hybrid/composable architecture. Best for large enterprises wanting composable data activation on top of existing cloud warehouses. |
| **[mParticle](https://www.mparticle.com/)** | $300M (Acquired by Rokt) | ~$3,000/mo (estimated entry contract based on mParticle Credits) | 14-day sales-assisted developer sandbox POC (no self-serve free tier) | Customer data platform tailored for mobile-first and omnichannel identity resolution. Best for mobile-first apps needing real-time audience segmentation and SDK pipelines. |
| **[RudderStack](https://www.rudderstack.com/)** | ~$300M Valuation ($82M Raised) | $265/mo (Growth tier) | Free forever: 250,000 events/mo (plus 14-day free trial of Growth tier; open-source core is 100% free) | Warehouse-first customer data pipeline. Best for engineering and data teams building a Segment alternative directly in Snowflake, BigQuery, or Databricks. |



## Open-Source GitHub Projects



- **[Apache Unomi](https://github.com/apache/unomi)**

  **Java Open Source Customer Data Platform** (Apache 2.0) — **the most mature open-source CDP** and a reference implementation of the OASIS CDP standard . **Features**: Unified persistent profiles across anonymous and identified visitors, real-time segmentation and scoring, GDPR consent management as a first-class feature, REST/JSON API for any integration, Elasticsearch backend, and plugin architecture extensible without forking . **Tech stack**: Java (Apache Karaf OSGi), Elasticsearch. **Deploy**: Self-hosted (Docker image available) . **Adoption**: Used by City of Munich for web personalization and by Jahia, Ninetailed, and Dropsolid in commercial products . **Best for**: organizations wanting a standards-compliant, privacy-first CDP with proven production deployments.



- **[RudderStack](https://github.com/rudderlabs/rudder-server)**

  **Warehouse-first Customer Data Pipeline and Segment alternative** (AGPL-3.0 for core) — **the most widely adopted open-source event pipeline** with ~4,150 GitHub stars . **Features**: Collects and routes clickstream data from web, mobile, and server sources; builds customer data lake directly in your warehouse (Snowflake, BigQuery, Redshift); extensive SDK coverage (JavaScript, iOS, Android, React Native, Flutter, Go, Node, Rust, Unity, Kotlin) ; privacy and security focused. **Tech stack**: Go (server), TypeScript (transformer), React. **Deploy**: Self-hosted (Docker, Kubernetes) or RudderStack Cloud. **Best for**: data teams wanting to own their event pipeline and build customer data infrastructure in their warehouse without per-event SaaS costs.



- **[Tracardi](https://github.com/Tracardi/tracardi)**

  **Composable API-first Customer Data Platform** (license per repo) — **a flexible, developer-oriented CDP** with ~476 GitHub stars . **Features**: Customer data unification, event tracking, segmentation, and workflow automation; API-first design for integration with any stack; GUI available via separate `tracardi-gui` repository. **Tech stack**: Python. **Deploy**: Self-hosted. **Best for**: developers wanting a Python-based CDP with workflow automation capabilities and full API control.



- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**

  **AI-first Customer Data Platform framework** (license per repo) — **a comprehensive, self-hosted CDP with ML and big data at its core** . **Features**: Omnichannel data collection (web, mobile, CRM, POS, e-commerce, social, IoT), real-time Customer 360, ML-based segmentation (RFM, CLV, churn prediction, lead scoring), behavioral tracking and journey mapping, real-time audience activation, and Agentic AI/LLM-powered personalization. **Tech stack**: Multi-component (Dagster for orchestration, Docker/Kubernetes). **Deploy**: Self-hosted. **Note**: Ambitious scope; evaluate maturity and component integration before production adoption. **Best for**: organizations wanting an AI-native CDP framework they can customize and extend.



- **[Multiwoven](https://github.com/Multiwoven/multiwoven)**

  **Open-source Reverse ETL and data activation platform** (AGPL-3.0) — **the leading open-source alternative to Hightouch and Census** . **Features**: Sync data from warehouse (Snowflake, Redshift, BigQuery, Databricks, PostgreSQL) to business tools; visual model builder with SQL or dbt; connectors for CRM (Salesforce, HubSpot), marketing (Braze, Klaviyo), support (Zendesk, Intercom), ads (Google Ads, Facebook Ads), and collaboration (Slack, Sheets) . **Tech stack**: Ruby (server), React (UI). **Deploy**: Self-hosted (Docker Compose, Helm charts, cloud VM guides). **Best for**: data teams wanting to activate warehouse data without SaaS per-row pricing—**complements a CDP** rather than replacing one.



- **[MessageBirds](https://github.com/Mullassery/MessageBirds)**

  **Event-driven Customer Data & Engagement Platform** (license per repo) — **a modern Rust-based CDP with identity resolution and journey orchestration** . **Features**: Identity graph with deterministic matching and merge/split audit trails, schema registry with field-level governance labels, real-time audience evaluation, durable journey engine (Wait/Condition/Action/Split), consent ledger, and multi-SDK support (Web, iOS, Python, TypeScript). **Tech stack**: Rust (core), TypeScript (SDKs/UI), Kafka/Redpanda, PostgreSQL. **Deploy**: Self-hosted (Docker Compose for dev infra). **Note**: Early-stage project with disclosed unverified components (Android SDK, edge gateway not deployed) . **Best for**: developers wanting a modern, Rust-based CDP foundation with strong governance and journey capabilities.



### Additional Strong Open-Source Options



- **miniMDM** — Minimal Master Data Management application (license per repo) with lifecycle states, validation rules, audit logs, and REST API. **Note**: MDM, not CDP—manages master records (customer, product, vendor) with governance, not event-driven customer profiles . **Best for**: organizations needing lightweight MDM for customer master data governance.

- **drt (data reverse tool)** — CLI-based Reverse ETL (license per repo) for syncing warehouse data to external services via YAML. **Note**: Code-first, dbt-adjacent workflow; no GUI or CDP features . **Best for**: engineering teams wanting Git-native data activation without a UI.

- **Pimcore** — Open-source MDM/PIM/DAM/CDP platform (GPL-3.0) with customer data aggregation capabilities alongside product and asset management . **Best for**: organizations already using Pimcore for product data wanting customer master data in the same platform.



**Frameworks for building custom systems**: Combine **Apache Unomi** for standards-compliant profile unification and segmentation with **RudderStack** for event collection and warehouse routing, **Multiwoven** for warehouse-to-tool activation, and **Tracardi** or **LEO CDP** for workflow and AI-powered personalization—creating a comprehensive customer data stack matched to each organization's privacy and infrastructure requirements.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer data platforms handling personal data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate consent management, access controls, and data retention policies.

- **The "CDP vs. Reverse ETL vs. MDM" distinction matters.** **Apache Unomi, Tracardi, and LEO CDP** are **Customer Data Platforms**—they unify profiles, segment audiences, and enable real-time decisioning. **RudderStack** is a **data pipeline**—it collects and routes events but relies on your warehouse for storage and activation. **Multiwoven and drt** are **Reverse ETL**—they activate warehouse data to business tools but do not collect or unify customer profiles. **miniMDM and Pimcore** are **Master Data Management**—they govern master records but lack event-driven customer intelligence . **Choose based on whether you need unification, collection, activation, or governance.**

- **Apache Unomi is the most production-proven open-source CDP.** It is an OASIS standard reference implementation, used by the City of Munich, and powers commercial products from Jahia, Ninetailed, and Dropsolid . **The trade-off**: Java/OSGi stack requires operational expertise, and Elasticsearch is a hard dependency.

- **RudderStack is the most widely adopted open-source customer data project** (~4,150 stars), but it is a **pipeline**, not a full CDP . It excels at event collection and warehouse routing; for profile unification and segmentation, pair it with Unomi or query your warehouse directly.

- **LEO CDP and MessageBirds are ambitious but early-stage.** LEO CDP claims comprehensive AI and ML capabilities but has limited community validation . MessageBirds discloses unverified components and is not yet production-hardened . **Evaluate maturity carefully before trusting production customer data workflows.**

- **Pricing transparency varies across SaaS vendors.** Segment offers transparent MTU-based tiers; Salesforce Data Cloud uses credit-based consumption; most others (Tealium, mParticle, Treasure Data, Amperity, ActionIQ, Bloomreach, Workday) require sales contact. **Validate with direct vendor conversations against your actual data volumes and activation needs.**

- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Customer data is highly sensitive**—ensure your hosting meets your organization's security and privacy requirements before deploying.



---



**Made for developers, data teams, and organizations building transparent customer data solutions.**

Let's make Customer Data Management more open, data-driven, and privacy-friendly.
