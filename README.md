## Hey, I'm Enzo Avalos 👋
> **Data Platform Engineer**

I specialize in building high-throughput, decoupled distributed systems, optimizing cloud compute operations (Databricks/Spark Catalyst execution plans), and architecting declarative data quality pipelines. I focus on reducing distributed systems compute overhead and enforcing strict data governance at scale.

---

## 🚀 Core Technical Ecosystem

* **Big Data & Compute:** Databricks, Apache Spark, PySpark (Physical Plan & Shuffle Optimization), Delta Lake.
* **Modern Data Stack:** dbt Core, Dagster (Asset-Based Orchestration), Snowflake, Elementary Observability.
* **Data Governance:** Open Data Contract Standard (ODCS), Automated Metadata Scaffolding, Data Contracts.
* **Languages & Infrastructure:** Python, Advanced SQL (PostgreSQL, MySQL, SQL Server), Kotlin, Bash, Git.

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/Databricks-red?style=for-the-badge&logo=databricks&logoColor=red&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Spark-%23E25A1C?style=for-the-badge&logo=apachespark&logoColor=%23E25A1C&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Delta-%23003366?style=for-the-badge&logo=delta&logoColor=%23003366&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Snowflake-%2329B5E8?style=for-the-badge&logo=snowflake&logoColor=%2329B5E8&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/ODCS-%23CB171E?style=for-the-badge&logo=yaml&logoColor=%23CB171E&labelColor=black">
</p>

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=python&logoColor=%233776AB&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/SQL-blue?style=for-the-badge&logo=postgresql&logoColor=blue&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Bash-black?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Git-%23F03C2E?style=for-the-badge&logo=git&logoColor=white&labelColor=black">
    <img alt="Static Badge" src="https://img.shields.io/badge/Kotlin-%237F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=black">
</p>

---

## 🛠️ Selected Engineering Architectures

### 1. Enterprise DQX & Data Contract Framework
*Architected a Databricks-native data quality validation platform utilizing declarative configurations.*
* **Single-Pass Optimization:** Structured execution code to evaluate hundreds of complex data validations inside a single Spark physical plan, minimizing distributed shuffle overhead across massive datasets.
* **I/O Minimization:** Engineered cross-dataset rules using lazy PySpark operations and `ReuseExchange` nodes, capping disk reads to exactly 1 per dataset validation run.
* **Lineage Preservation:** Bypassed framework engine limitations by utilizing internal closure dictionary references (`ref_dfs`) to isolate granular row-level errors without corrupting the production catalog target schema.
* **Deterministic Telemetry:** Built a three-tiered Delta Lake logging architecture (Macro/Meso/Micro analytics) cross-referenced via unique SHA-256 hashes for cryptographic traceability.

### 2. Airbnb Berlin Insights Pipeline
*An end-to-end production-grade analytics platform showcasing advanced modern data stack implementation.*
* **Orchestration:** Built asset-based data pipelines using **Dagster** to manage **dbt Core** execution nodes over a **Snowflake** data warehouse.
* **Historical Tracking:** Implemented robust Slowly Changing Dimensions (SCD Type 2) tracking for dynamic listing properties.
* **Observability:** Integrated **Elementary** with automated operational Slack alerting, generating performance audit tables detailing invocation telemetry.
* **Analytics Layer:** Developed centralized marts evaluating dimensional cross-sections, exposed via interactive analytics dashboards in **Preset**.

---

## 📈 Open-Source Status & Telemetry

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=enzoavalos&theme=highcontrast" alt="GitHub Streak" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=enzoavalos&layout=compact&theme=highcontrast" alt="Top Langs" width="48%" />
</p>

## 📫 Let's Build Something High-Scale:

* **LinkedIn:** [linkedin.com/in/enzo-g-avalos](https://www.linkedin.com/in/enzo-g-avalos)
* **Email:** [avalos.enzo.g@gmail.com](mailto:avalos.enzo.g@gmail.com)
