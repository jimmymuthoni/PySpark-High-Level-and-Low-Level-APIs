# Apache Spark Overview 🚀

This repository contains learning materials and code related to **Apache Spark**, a unified analytics engine for large-scale data processing. All exercises and experiments were performed using **Google Cloud Platform (GCP) Dataproc clusters**, enabling distributed computing in a real-world cloud environment with **Hadoop Distributed File System (HDFS)** as the underlying storage.

---

## 🔍 Overview

Apache Spark is an open-source distributed computing system that provides fast and general-purpose cluster computing. This repo covers:

- High-level APIs: Spark SQL & DataFrames
- Low-level APIs: RDDs (Resilient Distributed Datasets)
- Cloud-based execution using GCP Dataproc
- Data processing on HDFS

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

- **Google Cloud Platform (GCP) Dataproc Clusters** were used to deploy Spark.
- **Hadoop Distributed File System (HDFS)** served as the primary storage layer for distributed data.
- Real-world simulation of large-scale data processing pipelines in the cloud.

---

## 🛠️ Tools & Tech Stack

- Apache Spark(PySpark)
- Hadoop HDFS
- Google Cloud Platform (Dataproc)
- Jupyter Notebook
- Python

---
