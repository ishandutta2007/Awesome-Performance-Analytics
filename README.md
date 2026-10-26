# Awesome-Performance-Analytics

# Top Performance Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on KPI Tracking, Business Intelligence & Self-Service Dashboards*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Performance Analytics**. These tools enable organizations to define key performance indicators, track trends over time, build interactive dashboards, and derive actionable insights from business and operational data for strategic decision-making and continuous improvement.

**Examples** include ServiceNow Performance Analytics, Tableau, Microsoft Power BI, Looker, Qlik Sense, Sisense, Domo, ThoughtSpot, GoodData, and MicroStrategy (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted business intelligence, KPI dashboards, and embedded analytics—ideal for organizations building sovereign analytics infrastructure without per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Performance Analytics](https://www.servicenow.com/)**  
  Paid analytics module on the Now Platform for tracking business process KPIs (Incident, Change, Request) over time using indicators, scorecards, historical data collection, forecasting, and threshold alerts; the data engine that plugs into the newer Platform Analytics frontend for advanced insights and continuous service improvement .

- **[Tableau](https://www.tableau.com/)**  
  Enterprise visual analytics platform with VizQL for deep interactive exploration, Tableau Catalog for data lineage and metric governance, row-level security for multi-business-line deployment, and mature AI-assisted chart generation; best suited for organizations with dedicated analyst resources and high visual granularity requirements .

- **[Microsoft Power BI](https://powerbi.microsoft.com/)**  
  Microsoft-ecosystem BI platform with shared semantic models for consistent metric definitions, deployment pipelines for dev/test/prod isolation, Copilot AI for natural language report creation and DAX generation, and monthly release cadence; Pro at $14/user/month with broad enterprise adoption and job market dominance .

- **[Looker](https://looker.com/)**  
  Google Cloud BI platform built on LookML, a centralized semantic modeling language for governed, reusable metric definitions; strongest when standardized on BigQuery and Google Cloud, with a developer-oriented approach to metric consistency across analyst teams .

- **[Qlik Sense](https://www.qlik.com/)**  
  Associative analytics engine where every field is automatically associated with every other field, enabling exploration without predefined queries; well-suited for complex many-to-many data relationships that resist traditional star-schema modeling .

- **[Sisense](https://www.sisense.com/)**  
  BI and analytics platform (ISG Buyers Guide Leader) with embedded analytics capabilities and a fusion data model for combining disparate sources .

- **[Domo](https://www.domo.com/)**  
  Cloud BI platform ranked third overall in ISG's 2026 GenAI analytics provider assessment, with Exemplary classification across product and customer experience; known for broad connector library and business-user-friendly dashboard creation .

- **[ThoughtSpot](https://www.thoughtspot.com/)**  
  Search-driven analytics platform with natural language querying and AI-powered insights, classified as Exemplary in ISG's GenAI analytics evaluation .

- **[GoodData](https://www.gooddata.com/)**  
  Embedded analytics and BI platform (ISG Merit classification) focused on multi-tenant, white-label analytics for SaaS products .

- **[MicroStrategy](https://www.microstrategy.com/)**  
  Enterprise BI platform with AI-powered analytics (MicroStrategy ONE), classified as Exemplary in ISG's 2026 GenAI analytics evaluation with strong customer experience scores .

## Open-Source GitHub Projects

- **[Apache Superset](https://github.com/apache/superset)**  
  Leading open-source BI and data visualization platform (Apache 2.0) with 40+ chart types, SQL Lab IDE, enterprise-grade role-based access control (Admin/Alpha/Gamma/Public), row-level security, and native support for cloud warehouses; v6.0 shipped December 2025 with v7 in development; the most comprehensive Tableau/Looker-like open-source experience, though it requires SQL fluency and heavier infrastructure (app server, metadata DB, Redis, Celery workers) .

- **[Metabase](https://github.com/metabase/metabase)**  
  Open-source BI tool (AGPL) designed for non-technical users with a visual query builder, easy setup (one app plus a database), and free AI SQL in the OSS tier as of v59; the lightest self-hosting option and the best fit for mixed teams where business users need self-service analytics; embedded white-labeling requires the Pro plan .

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source observability platform (AGPL v3) optimized for time-series metrics and infrastructure monitoring; excellent for real-time KPI dashboards over Prometheus, InfluxDB, and Loki, but not a general-purpose business analytics tool—answering "revenue by plan this quarter" in Grafana is fighting the tool .

- **[Lightdash](https://github.com/lightdash/lightdash)**  
  Open-source BI platform purpose-built for dbt workflows; metrics are defined in version-controlled dbt YAML, ensuring consistent definitions across dashboards; features AI Agents that understand the data model and SOC 2 compliance for enterprise sales; ideal for teams already running dbt .

- **[Cube.js](https://github.com/cube-js/cube)**  
  Open-source headless semantic layer that sits between data sources and any visualization layer; ensures consistent metric definitions across multiple tools, supports row-level security via Authz SDK, and enables sub-second queries through WASM-based SQL transpilation; use when building embedded analytics or when metric consistency across tools is the priority .

- **[Evidence.dev](https://github.com/evidence-dev/evidence)**  
  Code-first, analytics-as-code BI framework; dashboards are written in Markdown with SQL queries, version-controlled in Git, and rendered as static sites; ideal for developer-focused teams wanting Git-native workflows and reproducible analytics .

- **[Wren AI](https://github.com/Canner/WrenAI)**  
  Open-source AI-native BI platform enabling natural language querying without SQL; builds a semantic layer that feeds both human users and AI agents; suited for organizations wanting to democratize data access for non-technical users through conversational analytics .

### Additional Strong Open-Source Options

- **Rill Data** — Code-driven dashboards built on DuckDB/ClickHouse with YAML/SQL definitions; for teams wanting Evidence.dev philosophy with more dashboard flexibility .
- **DataEase** — Open-source BI tool (Chinese ecosystem) positioned as more user-friendly than Superset and Metabase for non-technical users; active domestic community and installation base .
- **Redash** — SQL-first dashboard tool; note that development has slowed significantly (three releases 2025–2026 after four years of inactivity), and it is no longer recommended for new deployments .

**Frameworks for building custom systems**: Combine **Apache Superset** for heavy SQL analytics over a warehouse, **Metabase** for self-service business user dashboards, **Lightdash** or **Cube.js** for governed metric definitions via semantic layers, and **Grafana** for real-time infrastructure KPIs in a self-hosted performance analytics stack tailored to different user skill levels and data volumes.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Performance analytics platforms handling business and operational data must comply with applicable privacy regulations and organizational data governance policies; row-level security and audit logging are essential for multi-tenant deployments.
- Self-hosted open-source solutions vary significantly in operational complexity—Metabase is lightweight, while Superset requires substantial infrastructure and SQL expertise; choose based on team capacity and analytical depth requirements.
- Verify license terms for commercial use; Superset uses Apache 2.0, Metabase uses AGPL with paid Pro/Enterprise tiers, and Grafana uses AGPL v3.

---

**Made for data analysts, BI developers, operations managers, and business intelligence leaders.**  
Let's make performance analytics more open, governed, and insight-driven.
