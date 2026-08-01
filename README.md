<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=280&section=header&text=Atharva%20R.%20Korwar&fontSize=46&fontColor=00F5D4&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20%7C%20Analytics%20Engineer%20%7C%20BI%20Engineer&descAlignY=55&descSize=18&descColor=B0FFF4" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2600&pause=900&color=00F5D4&center=true&vCenter=true&width=750&lines=Engineering+Cloud-Native+ELT+Pipelines...;Building+Star-Schema+Data+Warehouses...;Azure+%C2%B7+Databricks+%C2%B7+PySpark+%C2%B7+SQL+%C2%B7+Power+BI...;Turning+Raw+Data+Into+Business+Decisions...;Data+Engineering+%C3%97+Analytics+Engineering" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/atharvakorwar51237)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atharvakorwar51237@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Atharva-512)

<br/>

<img src="https://komarev.com/ghpvc/?username=Atharva-512&style=for-the-badge&color=00F5D4&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/Atharva-512?style=for-the-badge&color=00F5D4&label=FOLLOWERS&logo=github" />

</div>

<br/>

## `01` &nbsp;Engineering Philosophy

> Data engineering is a chain of trust, not a chain of scripts. Every stage — ingestion, cleaning, modeling, serving — either preserves that trust or breaks it. Pipelines are built idempotent and incremental by default, warehouses are modeled around business logic (not source-system structure), and reporting is treated as part of the engineering — not an afterthought.

<div align="center">

```mermaid
%%{init: {'theme':'dark', 'themeVariables': { 'primaryColor':'#302b63','edgeLabelBackground':'#0f0c29','fontFamily':'Fira Code'}}}%%
flowchart LR
    A[("Raw Data")] --> B["🥉 Bronze<br/>Ingestion"]
    B --> C["🥈 Silver<br/>Cleaning · Validation"]
    C --> D["🥇 Gold<br/>Business-Ready Models"]
    D --> E[("⭐ Warehouse<br/>Star Schema")]
    E --> F["📊 Analytics<br/>Dashboards · Decisions"]

    style A fill:#0f0c29,stroke:#00F5D4,color:#00F5D4
    style B fill:#302b63,stroke:#CD7F32,color:#fff
    style C fill:#302b63,stroke:#C0C0C0,color:#fff
    style D fill:#302b63,stroke:#FFD700,color:#fff
    style E fill:#0f0c29,stroke:#00F5D4,color:#00F5D4
    style F fill:#302b63,stroke:#00F5D4,color:#00F5D4
```

</div>

<br/>

## `02` &nbsp;Current Focus

<table>
<tr>
<td width="50%" valign="top">

**🎯 Building**
- Scalable cloud-native data platforms on Azure
- Distributed processing with Databricks + PySpark
- Dimensional data modeling & modern ELT
- Executive-grade BI dashboards

</td>
<td width="50%" valign="top">

**📈 Snapshot**
- `3` production-style ELT/ETL pipelines shipped
- `100K+` records processed in Azure pipeline
- `14` reporting views across a star-schema warehouse
- `National Finalist` — Smart India Hackathon

</td>
</tr>
</table>

<br/>

## `03` &nbsp;Technical Toolbox

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,java&theme=dark" height="45"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" height="28"/>

**Cloud & Data Engineering**
<br/>
<img src="https://skillicons.dev/icons?i=azure,gcp,docker&theme=dark" height="45"/>
<img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" height="28"/>

**Databases & Warehousing**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb&theme=dark" height="45"/>
<img src="https://img.shields.io/badge/Azure%20Synapse-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white" height="28"/>

**BI, Analytics & DevOps**
<br/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" height="28"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/DAX-217346?style=flat-square&logo=microsoftexcel&logoColor=white" height="28"/>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,jupyter&theme=dark" height="45"/>

</div>

<br/>

## `04` &nbsp;Featured Projects

<table>
<tr>
<td width="100%">

### 🍽️ Restaurant POS ELT Pipeline & Analytics Warehouse
**Problem →** Restaurant operators reconciled sales, ops, and KPI reports manually across disconnected POS exports.
**Built →** A production-grade, metadata-driven ELT pipeline staging raw POS reports into an analytics-ready DuckDB warehouse.
**Impact →** One automated source of truth for sales performance, ops efficiency, and KPI reporting — replacing manual reconciliation entirely.
**Architecture →** Bronze → Silver → Gold staging · Star schema — 3 fact tables, 6 dimension tables, 14 reporting views · Containerized, CI-automated deployment · 3 interactive Power BI dashboards.

`Python` `SQL` `Pandas` `DuckDB` `Apache Parquet` `Power BI` `Docker` `GitHub Actions`

[![Repo](https://img.shields.io/badge/View%20Repository-00F5D4?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Atharva-512/restaurant-pos-elt-pipeline)

</td>
</tr>
<tr>
<td width="100%">

### ☁️ End-to-End E-Commerce Data Pipeline on Azure (Olist)
**Problem →** E-commerce order data lived across HTTP APIs and SQL Server with no unified, low-latency reporting layer.
**Built →** Parameterized Azure Data Factory pipelines ingesting 100K+ order records into a Databricks-processed, Synapse-served warehouse.
**Impact →** Reliable, low-latency business reporting at scale with fault-tolerant multi-source ingestion.
**Architecture →** Medallion architecture on Databricks (PySpark) · Partitioned Synapse SQL views · Fault-tolerant batch ingestion into ADLS Gen2.

`Azure Data Factory` `ADLS Gen2` `Azure Databricks` `PySpark` `Synapse Analytics` `MongoDB` `Power BI`

[![Repo](https://img.shields.io/badge/View%20Repository-00F5D4?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Atharva-512/azure-ecommerce-data-pipeline)

</td>
</tr>
<tr>
<td width="100%">

### 🛍️ Retail Sales Analytics Platform
**Problem →** Retail transaction data held revenue and segmentation insight that wasn't surfaced anywhere.
**Built →** SQL and Python-driven analysis of 2,000+ transactions feeding interactive Power BI dashboards.
**Impact →** Revenue trends, customer segments, and discount impact surfaced across 6 categories, 5 regions, 3 channels to support growth decisions.
**Architecture →** SQL-based ETL workflows · EDA & statistical analysis for analytics-ready datasets · KPI-tracking executive dashboards.

`SQL` `Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Power BI` `MySQL` `Jupyter`

[![Repo](https://img.shields.io/badge/View%20Repository-00F5D4?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Atharva-512/retail-sales-analytics-platform)

</td>
</tr>
</table>

<br/>

## `05` &nbsp;Engineering Focus Matrix

| Area | Focus |
|---|---|
| ☁️ Cloud Data Engineering | Azure Data Factory · Azure Databricks · ADLS Gen2 |
| 🏛️ Data Warehousing | Azure Synapse Analytics · DuckDB · Star Schema Modeling |
| ⚡ Distributed Processing | PySpark · Staged Batch Pipelines |
| 🧮 Analytics Engineering | SQL Modeling · Data Quality · Incremental Processing |
| 📊 Business Intelligence | Power BI · Tableau · DAX · KPI Reporting |
| 🔁 Pipeline Automation | Docker · GitHub Actions · CI/CD |

<br/>

## `06` &nbsp;GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Atharva-512&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F5D4&icon_color=00F5D4&text_color=C9D1D9&count_private=true" height="170" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Atharva-512&theme=tokyonight&hide_border=true&background=0D1117&stroke=00F5D4&ring=00F5D4&fire=00F5D4&currStreakLabel=00F5D4" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Atharva-512&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F5D4&text_color=C9D1D9&langs_count=8" height="170" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Atharva-512&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=00F5D4&line=00F5D4&point=B0FFF4" width="95%"/>

<img src="https://github-profile-trophy.vercel.app/?username=Atharva-512&theme=tokyonight&no-frame=true&column=7&margin-w=8&margin-h=8" width="95%"/>

</div>

<br/>

## `07` &nbsp;Certifications

- 🎓 **Big Data Engineering Bootcamp with GCP & Azure Cloud** (74 Hours) — Udemy
- 🎓 **Ultimate Job-Ready AI-Powered Data Analytics Course** — CodeWithHarry

<br/>

<div align="center">

## Let's Build Something Data-Driven

Open to conversations on data engineering, analytics platforms, and cloud architecture.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/atharvakorwar51237)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atharvakorwar51237@gmail.com)

<br/><br/>

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

</div>
