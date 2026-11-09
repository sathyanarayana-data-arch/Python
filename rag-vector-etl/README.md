# Project 4: RAG Data Pipeline & Vector ETL for GenAI

## 📌 Overview
Modern data engineering pipeline designed for Artificial Intelligence—parsing and indexing unstructured text data for LLM applications.

## 🏗️ Architecture Flow
`Scraped Documents / PDFs` ➔ `Python Chunking & Cleansing` ➔ `Embedding Generation Model` ➔ `Vector Database`

## 🛠️ Tech Stack
* **Language:** Python
* **LLM Orchestration:** LangChain / LlamaIndex
* **Vector Store:** PostgreSQL with `pgvector` / Qdrant / Pinecone
* **Pipeline Orchestration:** Apache Airflow

## ⚙️ Key Skills Demonstrated
* **Unstructured Data Pipelines:** Extracting and parsing complex document hierarchies into clean, token-optimized text chunks.
* **Vector Operations:** Managing high-dimensional vector embeddings, optimizing indexing algorithms, and setting up metadata filtering for Retrieval-Augmented Generation (RAG).
