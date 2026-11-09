# Project 1: The Modern Cloud Lakehouse & ELT Pipeline

## 📌 Overview
A scalable end-to-end data platform mimicking modern enterprise data warehousing workflows.

## 🏗️ Architecture Flow
`REST API / Public Dataset` ➔ `Python Ingestion` ➔ `AWS S3 / ADLS Gen2 (Bronze Layer)` ➔ `Snowflake / Databricks Delta Lake (Silver & Gold Layers via dbt)`

## 🛠️ Tech Stack
* **Languages:** Python, SQL
* **Data Platform:** Snowflake / Databricks (Delta Lake)
* **Transformation Engine:** dbt-core
* **Orchestration:** Apache Airflow

## ⚙️ Key Skills Demonstrated
* **Data Modeling:** Star Schema implementation (Fact & Dimension tables) inside dbt using incremental models and snapshots (SCD Type 2).
* **Transformation Quality:** Custom dbt data quality tests, documentation, and data lineage tracking.
* **Orchestration:** Airflow DAG design with task dependencies, retry policies, and automated failure alerts.
