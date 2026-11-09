# Project 2: Real-Time CDC & Distributed Stream Processing

## 📌 Overview
Low-latency event processing system for high-volume financial transactions, tracking data changes as they happen.

## 🏗️ Architecture Flow
`Mock Transactional DB (PostgreSQL)` ➔ `Debezium (Change Data Capture)` ➔ `Apache Kafka` ➔ `PySpark Structured Streaming` ➔ `Analytical Storage (Delta Lake)`

## 🛠️ Tech Stack
* **Containerization:** Docker Compose
* **Source Database:** PostgreSQL
* **Event Streaming & CDC:** Apache Kafka, Debezium
* **Processing Framework:** PySpark (Structured Streaming)
* **Storage Layer:** Delta Lake

## ⚙️ Key Skills Demonstrated
* **Streaming Architecture:** Handling unbounded data streams, managing watermarks, and resolving late-arriving records.
* **Distributed Compute:** PySpark streaming jobs for data cleansing, micro-batch aggregation, and transformations.
* **Infrastructure:** Multi-service local ecosystem orchestration using Docker Compose.
