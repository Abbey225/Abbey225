# Hi there, I'm Abbey! 👋

## ⚡ The Bridge: SSIS On-Premise to Modern Cloud Data Engineering & Data Science
I am a Data Engineer / Data Scientist with a strong foundation in traditional enterprise data integration (**SSIS / SQL Server**) who has transitioned into building code-first, scalable, cloud-native data pipelines (**Python, SQL, Docker, Databricks**). 

I specialize in translating drag-and-drop workflow patterns into robust, version-controlled code architectures that eliminate environment drift and scale effortlessly.

---

## 🛠️ Tech Stack & Skill Translation

| Enterprise ETL (SSIS / On-Prem) | Modern Data Engineering (Cloud-Native) |
| :--- | :--- |
| **Control Flow & SQL Agent** | Python Orchestration (Apache Airflow / Task Scheduling) |
| **Data Flow Task / Derived Column** | Clean Scripting (Python Requests, Pandas) & Modular SQL |
| **SQL Server Storage Layers** | Target Warehouses (PostgreSQL Containers, Snowflake, BigQuery) |
| **Staging → Warehouse Layers** | Databricks Lakehouse (Delta Lake, Medallion Architecture) |
| **Integration Services Catalog** | Version Controlled Environments (Git, GitHub, Docker Compose) |

---

## 🏗️ Featured Portfolio Projects

### 1. 🧱 [Databricks Medallion Lakehouse: Retail Star Schema](https://github.com/Abbey225/databricks-Projects
)
* **What it does:** A Bronze → Silver → Gold pipeline on Databricks that ingests raw customer, product, and order data, cleans and enriches it in the Silver layer, and models it into a star schema in Gold. Dimension tables (`dimcustomer`, `dimproducts`, `dimdate`) use auto-generated surrogate keys, and the `factorders` fact table resolves those keys through lookups. Every load is an idempotent Delta Lake `MERGE` upsert, so reruns insert new records and update changed ones without duplicates.
* **Tech Stack:** Databricks, Delta Lake, PySpark / Spark SQL, Unity Catalog, Medallion Architecture, Dimensional Modeling (Star Schema), Git.

### 2. 🛒 [End-to-End Retail Data Pipeline (ELT)](https://github.com/Abbey225/retail-delivery-pipeline)
* **What it does:** An automated pipeline that extracts raw e-commerce JSON data, ingests it into a local PostgreSQL data warehouse layer via Python, and normalizes it into analytical Fact and Dimension tables using structural SQL.
* **Tech Stack:** Python, PostgreSQL, SQL, Docker Compose, Git.

### 3. 📈 [Real-Time Crypto Data Streaming Pipeline](https://github.com/Abbey225/crypto-streaming-pipeline/tree/main/scripts)
* **What it does:** A micro-batch streaming engine that consumes live financial REST API tickers, handles low-latency transformation in-memory, and appends rows into a time-series optimized storage container.
* **Tech Stack:** Python (Requests / Time Loops), PostgreSQL, Docker, Git.

### 4. 🩺 [Data Quality & Automated Ingestion Pipeline](https://github.com/Abbey225/data-quality-ingestion-pipeline/tree/main/scripts)
* **What it does:** A robust Python ingestion gateway that intercepts incoming API payloads, runs structural validation checks to drop corrupted data, and logs clean records to the warehouse.
* **Tech Stack:** Python, PostgreSQL, Data Quality Gateways, Docker.

---

## 📫 Let's Connect!
* **LinkedIn:** [Connect with me on LinkedIn](https://linkedin.com)
* **Email:** obembeabiodunrotimi225@gmail.com
