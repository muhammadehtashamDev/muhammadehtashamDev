<!-- ============================================================
     GitHub README — Muhammad Ehtasham Khan (CV layout)
     Upload `profile.png`, `CV.pdf` and the `playground/` folder
     to the root of this repository next to this README.
     Then enable GitHub Pages and replace YOUR-USERNAME / YOUR-REPO
     in the playground link below (search for "YOUR-USERNAME").
     ============================================================ -->

<table width="100%">
  <tr>
    <td width="170" align="center" valign="middle">
      <img src="profile.png" alt="Muhammad Ehtasham Khan" width="160" />
    </td>
    <td valign="middle">
      <h1>MUHAMMAD EHTASHAM KHAN</h1>
      <b>DATABASE ARCHITECTURE &nbsp;|&nbsp; DATA ENGINEERING &nbsp;|&nbsp; BUSINESS INTELLIGENCE</b><br/>
      📍 Lahore, Pakistan &nbsp;•&nbsp; 🌍 Remote: USA (EST), EU, Canada &amp; Middle East<br/>
      ⏳ 13+ years across database platforms, data pipelines, analytics and enterprise operations
      <br/><br/>
      <img src="https://img.shields.io/badge/Experience-13%2B%20Years-1F3864?style=flat-square" />
      <img src="https://img.shields.io/badge/Upwork-%24100K%2B%20Earned-2E75B6?style=flat-square&logo=upwork&logoColor=white" />
      <img src="https://img.shields.io/badge/Upwork-6%2C300%2B%20Hours-2E75B6?style=flat-square&logo=upwork&logoColor=white" />
      <img src="https://img.shields.io/badge/Open%20to-Remote%20Work-1F3864?style=flat-square" />
      <br/>
      <!-- Add your contact links here (uncomment and replace the placeholders):
      <a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-Contact-1F3864?style=flat-square&logo=gmail&logoColor=white" /></a>
      <a href="https://www.linkedin.com/in/your-profile"><img src="https://img.shields.io/badge/LinkedIn-Connect-2E75B6?style=flat-square&logo=linkedin&logoColor=white" /></a>
      <a href="https://www.upwork.com/freelancers/your-profile"><img src="https://img.shields.io/badge/Upwork-Hire%20Me-14A800?style=flat-square&logo=upwork&logoColor=white" /></a>
      -->
      <a href="CV.pdf"><img src="https://img.shields.io/badge/Download-CV%20(PDF)-1F3864?style=flat-square&logo=adobeacrobatreader&logoColor=white" /></a>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://muhammadehtashamDev.github.io/muhammadehtashamDev/playground/">
    <img src="https://img.shields.io/badge/▶%20TRY%20IT%20LIVE-Query%20my%20career%20with%20SQL-2E75B6?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=1F3864" alt="Live SQL Playground" />
  </a>
  <br/>
  <sub>A real SQLite database of my CV, running in your browser. Pick a query or write your own. No sign-up.</sub>
</p>

```sql
-- ehtasham.db
SELECT name, role, years_experience, specialties
FROM   data_professionals
WHERE  skills @> ARRAY['Oracle','PostgreSQL','Snowflake','Airflow','Power BI']
  AND  rows_processed >= 200000000
  AND  open_to_remote = TRUE;

-- name                     | role                 | years | specialties
-- -------------------------+----------------------+-------+------------------------------------
-- Muhammad Ehtasham Khan   | Database Architect   |  13+  | Data Engineering, Warehousing, BI
-- (1 row)
```

---

## 👤 PROFESSIONAL PROFILE

Database Architect and Data Engineering professional with **13+ years** of experience spanning relational database design, SQL development, data integration, ETL/ELT, cloud data warehousing, BI reporting, and billing platforms. Builds dependable data architectures and reporting workflows, optimizes SQL workloads, and modernizes legacy data and reporting environments. Hands-on experience across **Oracle, PostgreSQL, MySQL, MariaDB, SQL Server, Snowflake, MongoDB and Neo4j**, with **Apache Airflow, Airbyte, Python, Power BI, SSRS, Pentaho and Looker Studio**. Also uses Claude-assisted workflows to accelerate analysis, documentation and development.

---

## 🧩 CORE ARCHITECTURE & DELIVERY STRENGTHS

| Area | Strengths |
|:--|:--|
| **Database Architecture & SQL** | Relational schema design, data modeling, SQL optimization, stored procedures, functions, triggers, bulk loading, Oracle PL/SQL, PostgreSQL, MySQL, SQL Server |
| **Data Engineering & Warehousing** | ETL/ELT, data integration, migration, orchestration, Snowflake, BigQuery, star schema, Airflow, Airbyte, Python |
| **BI, Analytics & Reporting** | Power BI, Looker Studio, SSRS, Pentaho PDI, Tableau, DAX, Power Query M, dashboards, reporting modernization |
| **NoSQL, Cloud & Automation** | MongoDB, Supabase, AWS, Azure, Databricks, Linux shell, API integration, data quality, AI-assisted development |

---

## 🔀 HOW I BUILD DATA PLATFORMS

```mermaid
flowchart LR
    subgraph SRC["📥 Sources"]
        A1[(Oracle / MySQL<br/>SQL Server)]
        A2[REST APIs<br/>& Webhooks]
        A3[CRMs & SaaS<br/>Pipedrive · Toast]
        A4[Files<br/>CSV · Excel]
    end
    subgraph ING["⚙️ Ingest & Orchestrate"]
        B1[Airbyte]
        B2[Python · Pandas]
        B3{{Apache Airflow<br/>scheduling · retries}}
    end
    subgraph WH["🏛️ Warehouse"]
        C1[(Snowflake)]
        C2[(PostgreSQL)]
        C3[(BigQuery)]
    end
    subgraph MOD["🧱 Model & Quality"]
        D1[Star Schema<br/>Data Vault]
        D2[Validation ·<br/>Dedup · Reconciliation]
    end
    subgraph SRV["📊 Serve"]
        E1[Power BI · DAX]
        E2[SSRS · Looker Studio]
        E3[🤖 AI / LLM<br/>natural-language SQL]
    end
    A1 & A2 & A3 & A4 --> B1 & B2
    B1 & B2 --> B3
    B3 --> C1 & C2 & C3
    C1 & C2 & C3 --> D1 --> D2
    D2 --> E1 & E2 & E3
```

---

## 💼 PROFESSIONAL EXPERIENCE

```mermaid
gantt
    title Career Timeline
    dateFormat YYYY-MM
    axisFormat %Y
    section Telecom
    Executive · Warid Telecom              :done, 2013-05, 2017-12
    Expert · Jazz Telecom                  :done, 2017-01, 2018-07
    Solution Architect · Ericsson          :done, 2019-08, 2023-02
    section Data & BI
    Database & BI Freelancer · Upwork      :active, 2020-09, 2026-11
    Database Architect · Convier Solutions :active, 2023-03, 2026-11
    Resource Specialist · SanoLiving       :done, 2025-07, 2026-09
```

<table width="100%">
<tr><td><b>DATABASE ARCHITECT &nbsp;|&nbsp; CONVIER SOLUTIONS</b><br/><sub>Lahore, Pakistan</sub></td><td align="right" width="190"><b>Mar 2023 – Present</b></td></tr>
</table>

- Lead database and reporting delivery across client projects including **Fandex, PrinterOn and The SalesChief**.
- Design database structures and data flows; manage endpoint extraction, bulk data loading and API availability monitoring.
- Maintain and modernize reporting environments, including migration from **Pentaho to SSRS**.
- Develop and optimize SQL objects including stored procedures, functions and triggers; support operational automation with Linux scripting.

<table width="100%">
<tr><td><b>DATABASE ARCHITECTURE &amp; BI PROFESSIONAL &nbsp;|&nbsp; UPWORK</b><br/><sub>Freelancer</sub></td><td align="right" width="190"><b>Sep 2020 – Present</b></td></tr>
</table>

- Earned **$100K+** on Upwork with **6,300+ hours** and long-term client relationships, including a database engagement spanning **5+ years / 3,900+ hours**.
- Built and maintained large-scale data systems including a warehouse processing **130M+ records** and deduplication and reconciliation involving **200M+ rows**.
- Ongoing and completed work includes PostgreSQL CRM development, Toast database architecture, Pipedrive Power BI reporting, Oracle database maintenance, and MySQL database optimization.
- **Industry Experience:** Sports & Sports Analytics, Healthcare & MedTech, E-commerce & Retail, Finance & FinTech, Logistics & Supply Chain, Hospitality & Restaurants, Telecommunications, Manufacturing, Education, and CRM/Enterprise Applications.

<table width="100%">
<tr><td><b>RESOURCE SPECIALIST &nbsp;|&nbsp; SANOLIVING</b><br/><sub>Remote, United States</sub></td><td align="right" width="190"><b>Jul 2025 – Sep 2026</b></td></tr>
</table>

- Managed data integration, transformation and delivery workflows supporting business reporting.
- Designed and maintained **Snowflake** data models and transformation logic for scalable analytics.
- Built scheduled ETL workflows with **Apache Airflow and Python**; implemented data-quality and validation checks.
- Developed **Power BI** reports and used Claude-assisted workflows for SQL development, analysis and documentation.

<table width="100%">
<tr><td><b>SOLUTION ARCHITECT – BILLING &amp; DUNNING &nbsp;|&nbsp; ERICSSON</b><br/><sub>Lahore, Pakistan</sub></td><td align="right" width="190"><b>Aug 2019 – Feb 2023</b></td></tr>
</table>

- Led billing infrastructure and payment integration initiatives, including bill-printing migration and provisioning gateway consolidation.
- Delivered **Google Play payment integration for Jazz Telecom** and configured GST tax-suspension workflows.
- Improved recurring operations through Linux shell scripting and cron-based automation.

<table width="100%">
<tr><td><b>EXPERT – IT BILLING &amp; CRM OPERATIONS &nbsp;|&nbsp; JAZZ TELECOM</b><br/><sub>Lahore, Pakistan</sub></td><td align="right" width="190"><b>Jan 2017 – Jul 2018</b></td></tr>
</table>

- Managed high-volume SIM-swap and franchise-consolidation operations and related customer-account data activities.
- Developed and tested operational processes in UAT, supported production deployment and reviewed pilot performance.

<table width="100%">
<tr><td><b>EXECUTIVE – BILLING &amp; OPERATIONS &nbsp;|&nbsp; WARID TELECOM</b><br/><sub>Lahore, Pakistan</sub></td><td align="right" width="190"><b>May 2013 – Dec 2017</b></td></tr>
</table>

- Conducted end-to-end testing for BSS hardware and system upgrades; coordinated with vendors and internal teams on UAT.
- Managed mediation and file-pulling configurations for new network nodes, including Ericsson data and LTE roaming; supported TABS and rating-server deployments.

---

## 🗂️ SELECTED PROJECT PORTFOLIO

<sub><b>DATABASE PLATFORMS • DATA PIPELINES • BUSINESS INTELLIGENCE</b></sub><br/>
Representative delivery across database architecture, enterprise reporting, analytics dashboards and automated data workflows.

### 🛢️ Database Architecture & Data Engineering

| Project | Description | Technologies |
|:--|:--|:--|
| **Fandex** – Sports Exchange Data Integration & API Monitoring | Built data flows to collect sports data from multiple endpoints, load it into a database and monitor API availability with automated alerts. | `SQL` `REST APIs` `Database Integration` `Linux Shell` |
| **The SalesChief** – Meeting Evaluation Platform | Designed database architecture, handled bulk loading and established data flows for a platform that evaluates meetings through randomized questions and response scoring. | `Database Design` `SQL` `Bulk Loading` `Data Integration` |
| **SanoLiving** – Snowflake Cloud Warehouse & ETL | Designed and maintained Snowflake data models, orchestrated scheduled pipelines, added validation checks and supported analytics reporting. | `Snowflake` `Apache Airflow` `Python` `Power BI` |
| **Oracle** – WhatsApp Invoice & Notification Integration | Integrated WhatsApp API workflows with Oracle database processes to send invoices and manage notification messages and campaign URLs through automated jobs. | `Oracle` `PL/SQL` `WhatsApp API` `Job Scheduling` |
| **PrinterOn** – Reporting Platform Modernization | Managed reporting operations and ETL processes, maintained business reports and migrated reporting from Pentaho to SSRS. | `Pentaho PDI` `SSRS` `SQL` `ETL` |
| **Admin Dept** – PostgreSQL & SQL Database Architecture | Database design and SQL development across relational systems, including schema structuring, query optimization, database objects, data loading and integration workflows. | `PostgreSQL` `Oracle` `MySQL` `SQL Server` `PL/SQL` |

### 📊 Business Intelligence & Dashboard Projects

| Project | Description | Technologies |
|:--|:--|:--|
| **Executive KPI & Operational Performance Dashboards** | Decision-ready reporting views bringing financial health, operational efficiency and performance indicators together for leadership and business teams. | `Power BI` `Looker Studio` `SQL` `KPI Design` |
| **E-commerce Analytics Dashboard** | Dashboard concept and reporting delivery for sales trends, order performance, product/category performance, customer behavior and revenue analysis. | `Looker Studio` `Power BI` `Data Modeling` `Ecommerce Metrics` |
| **Sales & Revenue Reporting** | Structured reporting for sales performance, revenue trends, channel comparisons and management-level summaries. | `Looker Studio` `Power BI` `SQL` `Data Visualization` |
| **Telecom Billing & Service Performance Reporting** | Reporting and operational analysis supporting billing performance, subscriber activity, service delivery and process monitoring. | `BI Reporting` `SQL` `SSRS` `Data Integration` |
| **X Telecom** – Business Intelligence Dashboard | Supported a BI platform consolidating financial health, operational efficiency and service-performance information into decision-ready reporting. | `Business Intelligence` `Data Analytics` `Dashboard Reporting` |

---

## 🗄️ MY CV AS A DATA MODEL

This is the schema behind the [live SQL playground](https://muhammadehtashamDev.github.io/muhammadehtashamDev/playground/). Try joining `projects` with `skills` to find where each tool was used.

```mermaid
erDiagram
    COMPANIES ||--o{ EXPERIENCE : employs
    EXPERIENCE ||--o{ ACHIEVEMENTS : delivers
    PROJECTS ||--o{ PROJECT_SKILLS : uses
    SKILLS ||--o{ PROJECT_SKILLS : "applied in"

    COMPANIES {
        int company_id PK
        text company
        text industry
        text location
    }
    EXPERIENCE {
        int exp_id PK
        int company_id FK
        text role
        date start_date
        date end_date
        bool is_current
    }
    ACHIEVEMENTS {
        int achievement_id PK
        int exp_id FK
        text description
    }
    PROJECTS {
        int project_id PK
        text project
        text client
        text category
    }
    SKILLS {
        int skill_id PK
        text skill
        text category
    }
    PROJECT_SKILLS {
        int project_id FK
        int skill_id FK
    }
```

---

## 📡 ADDITIONAL ENTERPRISE & TELECOM INITIATIVES

- **Telecom Bill Printing Migration:** Managed migration and configuration of bill-printing machinery while maintaining subscriber billing continuity.
- **Provisioning Gateway Consolidation:** Developed and tested consolidated provisioning setups to improve workflow reliability and efficiency.
- **Google Play Payment Integration:** Led setup and deployment of a payment process enabling subscriber billing through Google Play payment flows.
- **GST Tax Suspension & Billing Automation:** Configured GST suspension and subscriber billing adjustments; automated recurring tasks and reports.

---

## 🛠️ TECHNICAL TOOLKIT

**Relational Databases**<br/>
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/PL%2FSQL-1F3864?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/Progress%20SQL-5CE500?style=for-the-badge&logoColor=white" />

**NoSQL & Graph**<br/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />

**Data Engineering**<br/>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/Airbyte-615EFF?style=for-the-badge&logo=airbyte&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
<img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" />
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/ETL%2FELT-1F3864?style=for-the-badge" />
<img src="https://img.shields.io/badge/Star%20Schema-2E75B6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Data%20Vault-1F3864?style=for-the-badge" />

**BI & Visualization**<br/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" />
<img src="https://img.shields.io/badge/SSRS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/Pentaho-1F3864?style=for-the-badge" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
<img src="https://img.shields.io/badge/DAX-2E75B6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Power%20Query%20M-1F3864?style=for-the-badge" />
<img src="https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon%20QuickSight-232F3E?style=for-the-badge" />

**Cloud & Automation**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Linux%20Shell-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Cron-1F3864?style=for-the-badge" />
<img src="https://img.shields.io/badge/API%20Integration-2E75B6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" />
<img src="https://img.shields.io/badge/Power%20Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=claude&logoColor=white" />

---

## 🤖 AI-POWERED DATABASE & DATA INTELLIGENCE

- Integrated AI models such as **Claude and GPT** with databases, enabling users to ask business questions in natural language and retrieve meaningful insights from structured data.
- Developed AI-assisted workflows for database querying, data exploration, reporting, and business intelligence.
- Leveraged **Claude API, OpenAI API, Python, SQL**, and database integrations to connect AI capabilities with existing data systems.
- Applied AI to improve data accessibility, automate information retrieval, and support faster, data-driven decision-making.

---

## 🎓 EDUCATION

<table width="100%">
<tr><td><b>BS. Computer Science</b> – COMSATS University, Islamabad<br/><sub>Grade – A</sub></td><td align="right" width="190"><b>2009 – 2013</b></td></tr>
</table>

---

## 📜 CERTIFICATIONS

- ✅ Microsoft Azure Essentials
- ✅ Data Analytics for Business Professionals
- ✅ Claude Academy: Building with the Claude API
- ✅ Hands-on Advanced Python: Data Engineering

---

## 🌐 LANGUAGES

<table>
  <tr>
    <th rowspan="2">Language</th>
    <th colspan="2">UNDERSTANDING</th>
    <th colspan="2">SPEAKING</th>
    <th>WRITING</th>
  </tr>
  <tr>
    <th>Listening</th><th>Reading</th><th>Spoken production</th><th>Spoken interaction</th><th></th>
  </tr>
  <tr>
    <td><b>ENGLISH</b></td>
    <td align="center">C1</td><td align="center">C1</td><td align="center">C1</td><td align="center">C1</td><td align="center">C2</td>
  </tr>
</table>

<sub>Levels: A1 and A2: Basic user; B1 and B2: Independent user; C1 and C2: Proficient user</sub>

---

<p align="center">
  <b>MUHAMMAD EHTASHAM KHAN • DATABASE ARCHITECTURE &amp; BI</b>
</p>
