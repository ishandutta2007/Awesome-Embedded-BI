# Awesome-Embedded-BI

# 📊 Top Embedded BI



A curated list of **Embedded Business Intelligence (Embedded BI), customer-facing analytics, white-label analytics platforms, BI SDKs, and open-source alternatives** for integrating dashboards, reports, data exploration, and analytics directly into SaaS applications and enterprise software.



Embedded BI platforms typically provide **interactive dashboards, data visualization, self-service analytics, semantic modeling, drill-downs, filtering, multi-tenancy, row-level security, white-labeling, APIs, SDKs, and customer-facing analytics**.



> **Open-source software is the primary focus of this list.** The strongest open-source alternatives include **Apache Superset, Metabase, Lightdash, Cube, Grafana, Redash, Evidence, Rill, Helical Insight, and Knowage**. Some are complete BI platforms, while others are better suited as semantic layers, analytics backends, or developer-oriented building blocks.



## 📑 Table of Contents



* [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)

* [🌍 Open-Source](#-open-source)

* [🧩 Open-Source Embedded BI Building Blocks](#-open-source-embedded-bi-building-blocks)

* [🏗️ Embedded BI Architecture](#️-embedded-bi-architecture)

* [🔐 Multi-Tenant Embedded BI](#-multi-tenant-embedded-bi)

* [🔍 Commercial vs Open-Source](#-commercial-vs-open-source)

* [⭐ Recommended Open-Source Options](#-recommended-open-source-options)

* [🤝 How to Contribute](#-how-to-contribute)

* [⚠️ Disclaimer](#️-disclaimer)



---



## ☁️ SaaS/Hosted Platforms



| Platform | Description | Primary Focus | Pricing | Free Tier Limit |
| --- | --- | --- | --- | --- |
| [Sisense](https://www.sisense.com/) | Embedded analytics platform providing APIs, SDKs, dashboards, data modeling, visualization, and white-label analytics for software products. | ⭐ Embedded Analytics | Starts at ~$399/mo (Launch tier) / ~$10,000–$35,000/yr (Self-Serve base) | 7-day free trial ("Test Drive") with full access to Compose SDK and sandboxed analytics |
| [GoodData](https://www.gooddata.com/) | Developer-focused analytics platform providing embedded dashboards, analytics APIs, semantic modeling, metrics, and customizable analytics experiences. | Embedded BI, Headless Analytics | Starts at ~$1,500/mo (Professional tier per workspace) | 30-day free trial with full platform access (AI assistant, embedded dashboards, analytics APIs; no credit card required) |
| [Logi Analytics](https://insightsoftware.com/logi/) | Developer-oriented embedded analytics platform for integrating dashboards, reports, visualizations, and data experiences into applications. | Embedded BI | Starts at ~$100–$500/mo (Standard modules) / ~$16,000/yr (Base embedded deployment) | 15-day free trial license with evaluation software access |
| [Reveal BI](https://www.revealbi.io/) | Embedded analytics platform designed for integrating interactive dashboards, reports, visualizations, and analytics directly into applications. | Embedded BI | Starts at ~$9,995/yr (Flat annual fee per application with unlimited users) | 30-day free trial of SDK (license key required; full dashboard and embedding features) |
| [Looker Embedded](https://cloud.google.com/looker) | Google Cloud's embedded Looker analytics offering for integrating governed dashboards, explores, and analytics into applications. | Enterprise Embedded BI | Starts at ~$5,000/mo (~$60,000–$66,000/yr base platform + per-viewer licenses) | 30-day sales-assisted evaluation/POC instance (or free tier via Looker Studio for basic reporting) |
| [Qlik Embedded](https://www.qlik.com/us/products/qlik-embedded-analytics) | Developer platform for embedding Qlik analytics, visualizations, dashboards, and data experiences into applications. | Embedded Analytics | Starts at ~$300/mo (Qlik Cloud Analytics Standard, billed annually, 10 users, 10 GB data) | 30-day free trial with full access to Qlik Cloud Analytics, AI insights, and embedding APIs |
| [Domo Embedded](https://www.domo.com/platform/embedded-analytics) | Embedded analytics platform for integrating Domo dashboards, data applications, and analytics into customer-facing applications. | Embedded BI | Starts at ~$300/mo (Standard tier) / ~$50,000/yr (Enterprise consumption packages) | 30-day free trial with unlimited access to ETL, dashboards, connectors, and embedded features |
| [Yellowfin](https://www.yellowfinbi.com/) | Enterprise BI and embedded analytics platform providing dashboards, data storytelling, automated insights, and application-integrated analytics. | Embedded BI | Starts at ~$19/user/mo (or ~$3,000–$10,000/yr base server tier) | 30-day free trial with full visualization, dashboarding, and analytics features |
| [Bold BI](https://www.boldbi.com/) | Embedded analytics platform providing SDKs, APIs, dashboards, reports, data visualization, white-labeling, and multi-tenant analytics. | ⭐ Embedded BI | Free (Community) / Starts at ~$495/mo (~$5,940/yr flat license) | Free Community License (unlimited dashboards for 1 application for early-stage companies); 30-day free trial for Cloud/Enterprise |
| [Explo](https://www.explo.co/) | Developer-focused embedded analytics platform designed to add customer-facing dashboards and reporting to SaaS products. | SaaS Embedded Analytics | Free (Internal BI) / Starts at $695–$995/mo (Growth) / $1,995/mo (Pro embedded) | Free forever for internal BI (unlimited users & dashboards); 7-day free trial for customer-facing embedded analytics |
| [ThoughtSpot Embedded](https://www.thoughtspot.com/product/embedded) | Embedded analytics platform combining dashboards, search-driven analytics, AI-assisted insights, and data exploration. | AI Embedded Analytics | Free (Developer) / $25/user/mo (Essentials) / $0.10/credit (Pro consumption) / $12,999/yr (Startup) | Free Developer tier for 1 year (up to 10 users & 25M data rows); 14-day free trial for Enterprise |
| [Power BI Embedded](https://azure.microsoft.com/products/power-bi-embedded) | Microsoft Azure service for embedding Power BI reports and analytics into applications. | Enterprise Embedded BI | Starts at $1.01/hour (~$735/mo for 24/7 continuous A1 capacity SKU, pauseable when idle) | Free embed trial tokens for development and testing (watermarked trial banner; no production limit) |
| [Tableau Embedded Analytics](https://www.tableau.com/products/embedded-analytics) | Salesforce Tableau technology for embedding interactive analytics and dashboards into applications and portals. | Enterprise Embedded BI | Starts at ~$115/user/mo (Creator) / ~$35/user/mo (Viewer) / ~$60,000/yr (Embedded ISV agreement) | Free Developer Sandbox via Tableau Developer Program (includes Embedding Playground); 30-day general trial |
| [Domo Everywhere](https://www.domo.com/platform/embedded-analytics) | Domo's embedded analytics offering for integrating dashboards, data applications, and analytics into external products. | Embedded Analytics | Starts at ~$300/mo (Standard base) / ~$50,000/yr (Enterprise credit packages) | 30-day free trial with full platform access, Magic ETL, and external sharing |
| [Sisense Fusion](https://www.sisense.com/platform/) | Sisense's developer-focused analytics platform for integrating governed analytics and AI-powered insights into applications. | Developer BI | Starts at ~$399/mo (Launch) / ~$21,000–$35,000/yr (Fusion Developer / Self-Serve) | 7-day free trial sandbox with Compose SDK, Fusion data engine, and API access |
| [Phocas Embedded](https://www.phocassoftware.com/) | Embedded analytics platform for integrating dashboards, reporting, and business intelligence into operational software. | Embedded Analytics | Starts at ~$150/user/mo (or ~$1,800/yr per named user + base platform fee) | 30-day sales-assisted evaluation environment (or 30–60 min interactive live POC demo) |
| [Holistics](https://www.holistics.io/) | BI and embedded analytics platform providing data modeling, dashboards, reporting, and customer-facing analytics. | Embedded BI | Starts at $800/mo (billed annually at $9,600/yr) or $960/mo (Entry plan; Embedded add-on from $800/mo) | 14-day free trial with full feature access and no credit card required (extendable to 21 days on request) |
| [Embeddable](https://embeddable.com/) | Developer-first embedded analytics platform for building highly customizable customer-facing data experiences. | Developer Embedded BI | Starts at ~$499–$995/mo (Flat-rate session-based subscription) | 14-day developer trial / sandbox access to SDK, headless components, and live playground |
| [Luzmo](https://www.luzmo.com/) | Embedded analytics platform with dashboard embedding, interactive visualizations, data exploration, and application integration. | Embedded Analytics | Starts at $995/mo (~€1,995/mo for Pro, billed annually based on Monthly Active Viewers) | 10-day free trial with full access to dashboard editor, API integration, and dataset uploads |
| [Metabase Cloud](https://www.metabase.com/) | Hosted version of Metabase providing BI dashboards and analytics without managing the infrastructure. | Hosted BI | Starts at $90/mo (billed annually at $1,080/yr) or $100/mo (Starter plan with 5 users; Pro from $518/mo) | 14-day free trial of Metabase Cloud (no credit card required); Metabase Open Source is free forever (self-hosted) |
| [Preset](https://preset.io/) | Managed Apache Superset platform providing hosted dashboards and analytics infrastructure. | Managed Open-Source BI | Free (Starter) / Starts at $25/user/mo (Professional; Embedded add-on from $500/mo for 50 viewers) | Free forever Starter plan (up to 5 users, 1 workspace, unlimited charts/dashboards; hibernates after 30 days inactivity) |



---



## 🌍 Open-Source



> ⭐ **This is the primary section of this repository.**

>

> There is no single open-source project that perfectly replicates every capability of Sisense, GoodData, Looker Embedded, Qlik Embedded, or Domo Embedded. However, several projects provide extremely strong foundations for building an **open-source Embedded BI platform**.



| Project                                                             | Description                                                                                                                            | Best Use                          |

| ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |

| [Apache Superset](https://github.com/apache/superset)               | Apache-licensed BI platform with interactive dashboards, SQL exploration, visualization, APIs, and an official embedded-dashboard SDK. | ⭐ Embedded BI                     |

| [Metabase](https://github.com/metabase/metabase)                    | Popular open-source BI platform providing dashboards, visual query building, SQL analytics, APIs, and embedding capabilities.          | ⭐ Customer Analytics              |

| [Lightdash](https://github.com/lightdash/lightdash)                 | Open-source BI platform built around dbt and governed metrics, providing dashboards, explorations, and analytics applications.         | ⭐ Modern SaaS BI                  |

| [Cube](https://github.com/cube-js/cube)                             | Open-source semantic layer and analytics API platform for building custom analytics applications and embedded BI experiences.          | ⭐ Headless Embedded BI            |

| [Grafana](https://github.com/grafana/grafana)                       | Open-source visualization and dashboard platform with APIs, panels, data sources, and application integration capabilities.            | Operational / Embedded Dashboards |

| [Redash](https://github.com/getredash/redash)                       | SQL-first open-source query and visualization platform for building dashboards and data exploration experiences.                       | SQL-First BI                      |

| [Evidence](https://github.com/evidence-dev/evidence)                | Open-source code-first BI framework for creating analytics applications using SQL and Markdown-like components.                        | ⭐ Code-First BI                   |

| [Rill](https://github.com/rilldata/rill)                            | Open-source developer-focused BI platform for building fast dashboards and analytics applications on modern data infrastructure.       | Developer BI                      |

| [Helical Insight](https://github.com/helicalinsight/helicalinsight) | Open-source BI platform providing dashboards, reports, analytics, embedding, and customization capabilities.                           | Embedded / Enterprise BI          |

| [Knowage](https://github.com/KnowageLabs/Knowage-Server)            | Open-source enterprise BI platform supporting dashboards, reporting, analytics, data integration, and analytical applications.         | Enterprise BI                     |

| [Apache Zeppelin](https://github.com/apache/zeppelin)               | Open-source web-based notebook supporting interactive data exploration, visualization, SQL, and analytics.                             | Analytics Applications            |

| [Eclipse BIRT](https://github.com/eclipse-birt/birt)                | Open-source reporting and visualization platform designed for integration into Java applications.                                      | Embedded Reporting                |

| [JasperReports](https://github.com/TIBCOSoftware/jasperreports)     | Open-source Java reporting engine for generating and embedding reports in applications.                                                | Embedded Reporting                |

| [Pentaho Platform](https://github.com/pentaho/pentaho-platform)     | Open-source-oriented BI platform covering reporting, dashboards, analytics, and data integration.                                      | Enterprise BI                     |

| [Apache Superset UI](https://github.com/apache/superset)            | Superset's reusable visualization and analytics frontend components provide a foundation for customized analytics experiences.         | Custom BI                         |

| [Apache ECharts](https://github.com/apache/echarts)                 | Open-source visualization library for creating highly interactive charts and dashboards directly inside web applications.              | Visualization SDK                 |

| [Vega](https://github.com/vega/vega)                                | Open-source declarative visualization framework for building interactive visualizations.                                               | Visualization SDK                 |

| [Vega-Lite](https://github.com/vega/vega-lite)                      | High-level grammar for creating interactive visualizations that can be embedded into applications.                                     | Visualization SDK                 |

| [Plotly.js](https://github.com/plotly/plotly.js)                    | Open-source JavaScript visualization library for interactive charts and analytics interfaces.                                          | Visualization SDK                 |

| [Chart.js](https://github.com/chartjs/Chart.js)                     | Lightweight open-source charting library for custom embedded analytics interfaces.                                                     | Lightweight Visualization         |

| [D3.js](https://github.com/d3/d3)                                   | Low-level visualization toolkit for building completely customized analytics interfaces.                                               | Custom Analytics UI               |



---



## 🧩 Open-Source Embedded BI Building Blocks



An Embedded BI platform can be decomposed into several layers.



### 📊 Complete BI Platforms



These provide the largest portion of the functionality required for an Embedded BI product:



* [Apache Superset](https://github.com/apache/superset)

* [Metabase](https://github.com/metabase/metabase)

* [Lightdash](https://github.com/lightdash/lightdash)

* [Grafana](https://github.com/grafana/grafana)

* [Helical Insight](https://github.com/helicalinsight/helicalinsight)

* [Knowage](https://github.com/KnowageLabs/Knowage-Server)

* [Redash](https://github.com/getredash/redash)

* [Rill](https://github.com/rilldata/rill)

* [Evidence](https://github.com/evidence-dev/evidence)



---



### 🧠 Semantic Layer / Headless BI



For a SaaS company, a semantic layer can be more important than the dashboard UI itself.



* [Cube](https://github.com/cube-js/cube)

* [Lightdash](https://github.com/lightdash/lightdash)

* [dbt Core](https://github.com/dbt-labs/dbt-core)

* [Apache Superset](https://github.com/apache/superset)



A headless architecture allows the application to control the frontend:



```text

                    SaaS Application

                           │

                           ▼

                   Custom Analytics UI

                           │

                           ▼

                    Analytics API

                           │

                           ▼

                    Semantic Layer

                           │

                           ▼

                    Data Warehouse

```



This approach is particularly useful when a company wants the **analytics to feel like a native part of its product rather than an embedded third-party BI application**.



---



### 📈 Visualization Libraries



For companies that want complete control over the analytics UI:



* [D3.js](https://github.com/d3/d3)

* [Apache ECharts](https://github.com/apache/echarts)

* [Vega](https://github.com/vega/vega)

* [Vega-Lite](https://github.com/vega/vega-lite)

* [Plotly.js](https://github.com/plotly/plotly.js)

* [Chart.js](https://github.com/chartjs/Chart.js)



---



### 🗄️ Analytics Databases



High-performance analytical databases can provide the backend for a custom Embedded BI platform:



* [ClickHouse](https://github.com/ClickHouse/ClickHouse)

* [Apache Druid](https://github.com/apache/druid)

* [Apache Pinot](https://github.com/apache/pinot)

* [DuckDB](https://github.com/duckdb/duckdb)

* [Trino](https://github.com/trinodb/trino)

* [PostgreSQL](https://github.com/postgres/postgres)



---



## 🏗️ Embedded BI Architecture



A typical customer-facing Embedded BI architecture looks like:



```text

                         SaaS Application

                                │

                                ▼

                    ┌──────────────────────┐

                    │  Embedded Analytics  │

                    │       Frontend       │

                    └──────────┬───────────┘

                               │

                    ┌──────────┼──────────┐

                    │          │          │

                    ▼          ▼          ▼

                Dashboards   Charts    Filters

                    │          │          │

                    └──────────┼──────────┘

                               ▼

                    ┌──────────────────────┐

                    │   Analytics API      │

                    │       / SDK          │

                    └──────────┬───────────┘

                               │

                               ▼

                    ┌──────────────────────┐

                    │   Semantic Layer     │

                    │  Metrics / Models    │

                    └──────────┬───────────┘

                               │

                               ▼

                    ┌──────────────────────┐

                    │ Analytics Warehouse  │

                    └──────────────────────┘

```



---



## 🔐 Multi-Tenant Embedded BI



One of the biggest differences between ordinary internal BI and **Embedded BI** is the need to isolate analytics between customers.



```text

                       SaaS User

                           │

                           ▼

                    Application Login

                           │

                           ▼

                     Tenant ID

                           │

                           ▼

                    Embed Token / JWT

                           │

                           ▼

                 Embedded BI Application

                           │

                           ▼

                  Row-Level Security

                           │

                           ▼

                    Tenant Dataset

```



A production Embedded BI platform commonly needs:



* Tenant isolation

* Row-level security

* Role-based access control

* Attribute-based access control

* SSO

* OAuth / OIDC

* JWT authentication

* Short-lived embed tokens

* Dashboard-level permissions

* Dataset-level permissions

* Audit logging

* Usage tracking

* API authorization



---



## 🧱 Building an Open-Source Embedded BI Platform



A particularly interesting architecture is:



```text

                         Your SaaS Product

                                │

                                ▼

                         React / Vue UI

                                │

             ┌──────────────────┼──────────────────┐

             │                  │                  │

             ▼                  ▼                  ▼

        Dashboards           Charts             Filters

             │                  │                  │

             └──────────────────┼──────────────────┘

                                ▼

                         Analytics API

                                │

                                ▼

                       Cube / Lightdash

                                │

                                ▼

                         dbt / Semantic

                             Models

                                │

                                ▼

                       ClickHouse / Druid

                                │

                                ▼

                          Data Sources

```



Alternatively, an organization can embed a complete open-source BI platform:



```text

                         Your SaaS

                            │

                            ▼

                   Embedded BI Layer

                            │

              ┌─────────────┼─────────────┐

              │             │             │

              ▼             ▼             ▼

          Superset       Metabase      Lightdash

              │             │             │

              └─────────────┼─────────────┘

                            ▼

                     Data Warehouse

```



---



## 🔌 Embedded BI Integration Models



### 1. Dashboard Embedding



The simplest approach is to embed a pre-built dashboard.



```text

SaaS Application

       │

       └── Embedded Dashboard

               │

               ├── Charts

               ├── Filters

               └── Drilldowns

```



Best suited for:



* Customer reporting

* Executive dashboards

* Account dashboards

* Operational dashboards



---



### 2. Modular Embedding



Individual analytics components are embedded into the product.



```text

┌──────────────────────────────────────────┐

│              SaaS Product                │

│                                          │

│ Revenue       Users       Conversion     │

│ ┌───────┐     ┌───────┐   ┌──────────┐ │

│ │ Chart │     │ Chart │   │  Chart   │ │

│ └───────┘     └───────┘   └──────────┘ │

│                                          │

│              Customer Analytics          │

└──────────────────────────────────────────┘

```



This is closer to the experience provided by developer-oriented platforms such as **Sisense, GoodData, Bold BI, and Explo**.



---



### 3. Headless Analytics



The BI backend provides APIs while the SaaS application owns the entire UI.



```text

SaaS UI

   │

   ▼

Analytics API

   │

   ▼

Semantic Layer

   │

   ▼

Warehouse

```



This approach minimizes vendor lock-in and gives developers complete control over the product experience.



---



## 🔍 Commercial vs Open-Source



| Capability                | Commercial Embedded BI |   Open-Source Stack |

| ------------------------- | ---------------------: | ------------------: |

| Dashboard Embedding       |                      ✅ |                   ✅ |

| Interactive Dashboards    |                      ✅ |                   ✅ |

| Charts                    |                      ✅ |                   ✅ |

| Filters                   |                      ✅ |                   ✅ |

| Drill-Down                |                      ✅ |                   ✅ |

| Self-Service Analytics    |                      ✅ |                   ✅ |

| Semantic Layer            |                      ✅ |                   ✅ |

| APIs                      |                      ✅ |                   ✅ |

| SDKs                      |                    ⭐⭐⭐ |                  ⭐⭐ |

| White Labeling            |                    ⭐⭐⭐ |                  ⭐⭐ |

| Multi-Tenancy             |                    ⭐⭐⭐ |                   ✅ |

| Row-Level Security        |                      ✅ |                   ✅ |

| JWT / SSO                 |                      ✅ |                   ✅ |

| Custom Frontend           |                      ✅ |                 ⭐⭐⭐ |

| AI Analytics              |                    ⭐⭐⭐ |           ⚠️ Varies |

| Self-Hosting              |                 Varies |                 ⭐⭐⭐ |

| Source Code               |                      ❌ |                 ⭐⭐⭐ |

| Vendor Lock-in            |                 Higher |               Lower |

| Enterprise Support        |                    ⭐⭐⭐ | Community / Vendors |

| Infrastructure Management |                    Low |              Higher |

| Customization             |                   High |                 ⭐⭐⭐ |

| Licensing Cost            |                 Higher |               Lower |

| Engineering Cost          |                  Lower |              Higher |



> **Licensing matters.** "Open source" is not synonymous with "free commercial embedding." For example, Apache-licensed projects such as Superset are materially different from projects using copyleft or open-core licensing. Always check the current license and the specific embedding features you intend to use.



---



## ⭐ Recommended Open-Source Options



If the goal is specifically to build an **open-source alternative to Sisense, GoodData, Logi Analytics, Reveal BI, Looker Embedded, Qlik Embedded, or Domo Embedded**, these are the projects I would investigate first:



1. **[Apache Superset](https://github.com/apache/superset)** — ⭐ strongest overall open-source BI foundation for customizable dashboards and embedded analytics.

2. **[Metabase](https://github.com/metabase/metabase)** — ⭐ excellent choice when ease of use and self-service analytics are priorities.

3. **[Cube](https://github.com/cube-js/cube)** — ⭐ particularly compelling for a developer-first, headless Embedded BI architecture.

4. **[Lightdash](https://github.com/lightdash/lightdash)** — ⭐ strong choice for dbt-centric organizations and governed metrics.

5. **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** — strong open-source option for traditional BI, reporting, dashboards, and embedded use cases.

6. **[Grafana](https://github.com/grafana/grafana)** — excellent for operational and real-time embedded analytics.

7. **[Redash](https://github.com/getredash/redash)** — lightweight SQL-first BI and dashboarding.

8. **[Evidence](https://github.com/evidence-dev/evidence)** — excellent developer-first, code-based analytics.

9. **[Rill](https://github.com/rilldata/rill)** — modern developer-oriented BI for fast analytical applications.

10. **[Knowage](https://github.com/KnowageLabs/Knowage-Server)** — mature enterprise-oriented open-source BI platform.

11. **[Apache ECharts](https://github.com/apache/echarts)** — excellent if you want to build your own analytics frontend.

12. **[Vega](https://github.com/vega/vega)** — powerful declarative visualization framework.

13. **[Plotly.js](https://github.com/plotly/plotly.js)** — flexible interactive visualization layer.

14. **[D3.js](https://github.com/d3/d3)** — maximum flexibility for building a proprietary-looking analytics UX.

15. **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — strong analytical database foundation for high-scale customer-facing analytics.



---



## 💡 Three Open-Source Strategies



There are essentially **three ways to build an open-source alternative to commercial Embedded BI**.



### Strategy 1 — Embed a Complete BI Platform



```text

Your SaaS

   │

   └── Apache Superset / Metabase / Lightdash

              │

              ├── Dashboards

              ├── Charts

              ├── Filters

              ├── Drilldowns

              └── Analytics

```



**Best for:** getting a customer-facing analytics product running quickly.



---



### Strategy 2 — Headless BI



```text

Your SaaS

   │

   ├── React / Vue

   │

   ├── Custom Charts

   │

   ├── Cube

   │

   ├── dbt

   │

   └── ClickHouse

```



**Best for:** building something closer to **GoodData, Explo, or a developer-first Sisense-like platform**.



---



### Strategy 3 — Build the Entire Analytics Layer



```text

                 Your SaaS

                    │

          ┌─────────┴─────────┐

          ▼                   ▼

      Analytics UI        Analytics API

          │                   │

          └─────────┬─────────┘

                    ▼

              Semantic Layer

                    │

                    ▼

             Query Engine

                    │

                    ▼

            Analytics Database

```



Possible components:



* React / Vue

* D3.js / ECharts / Vega

* Cube

* dbt

* ClickHouse

* DuckDB

* PostgreSQL

* Trino



This provides the **maximum product control** but requires substantially more engineering.



---



## 🚧 Where Open Source Still Has Gaps



Commercial Embedded BI platforms can still have significant advantages in:



* Turnkey multi-tenancy

* White-label analytics

* Embedded dashboard builders

* Customer-facing self-service analytics

* Tenant provisioning

* Enterprise SSO

* Row-level security administration

* Analytics-specific SDKs

* Usage metering

* Embedded AI

* Product analytics UX

* Customer analytics administration

* Managed infrastructure

* Enterprise support

* SLAs

* Compliance certifications



This creates an interesting opportunity for an open-source platform that combines:



```text

Open-Source BI

      +

Headless Semantic Layer

      +

Embedded SDK

      +

Multi-Tenancy

      +

Row-Level Security

      +

White Label

      +

Analytics API

      +

AI Analytics

      =

Open-Source Embedded BI Platform

```



---



## 🤝 How to Contribute



Contributions are welcome! Please help expand this list with:



* Open-source Embedded BI platforms

* Open-source dashboard SDKs

* Open-source customer-facing analytics

* Headless BI platforms

* Semantic layers

* Embedded dashboard frameworks

* White-label analytics projects

* Multi-tenant analytics systems

* Row-level security implementations

* Analytics APIs

* React/Vue/Angular analytics components

* Open-source visualization libraries

* Open-source analytics databases

* Developer-first BI projects



### Contribution Guidelines



1. Fork this repository.

2. Add the project to the appropriate section.

3. Prefer projects with an active repository and a clearly stated license.

4. Clearly distinguish **fully open-source**, **open-core**, **source-available**, **commercial**, and **hosted-only** products.

5. Do not classify a proprietary hosted service as open-source merely because it provides an API or free tier.

6. Submit a pull request.



---



## ⚠️ Disclaimer



This repository is a **curated software directory**, not a product endorsement.



Licensing and embedding terms can differ substantially between projects. Some products use permissive open-source licenses, while others use copyleft, open-core, source-available, or proprietary licenses. Enterprise embedding, SSO, multi-tenancy, white-labeling, and other capabilities may also be commercially licensed.



Always verify the current license and commercial embedding terms before incorporating a project into a SaaS product.



**Last updated: August 2026**
