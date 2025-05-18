# Apache Spark Overview 🚀

This repository contains learning materials and code related to **Apache Spark**, a unified analytics engine for large-scale data processing. The practice and experiments were conducted on **Google Cloud Platform (GCP) Dataproc clusters**, enabling distributed computing in a real-world cloud environment.

---

## 🔍 Overview

Apache Spark is an open-source distributed computing system that provides fast and general-purpose cluster computing. This repo covers:

- High-level APIs: Spark SQL & DataFrames
- Low-level APIs: RDDs (Resilient Distributed Datasets)
- Cloud-based execution using GCP Dataproc

---

## 📘 High-Level APIs

### Spark SQL
- Executing SQL queries over structured data.
- Registering and querying temporary views and tables.
- Optimized query execution via Catalyst optimizer.

### Spark DataFrames
- Immutable distributed collection of data organized into named columns.
- Supports transformations like `select`, `filter`, `groupBy`, and joins.
- Supports reading/writing from various sources (CSV, JSON, Parquet).

---

## ⚙️ Low-Level APIs

### RDDs (Resilient Distributed Datasets)
- Fundamental data structure in Spark for low-level transformations.
- Operations include `map`, `flatMap`, `reduce`, `filter`, and `collect`.
- Offers more control over data processing and fault tolerance.

---

## ☁️ Cloud Setup

- **GCP Dataproc Clusters** were used for Spark cluster deployment.
- Notebooks and code executed on remote clusters to simulate production-like distributed data processing.

---

## 🛠️ Tools & Tech Stack

- Apache Spark( PySpark)
- Google Cloud Platform (Dataproc, GCS)
- Jupyter Notebook
- Python

---

