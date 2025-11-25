# Big Data – Final Project (Option A) – Apache NiFi

## 1. Project title and short description

**Title:** Data Ingestion Pipeline with Apache NiFi (Docker)

**Description:**  
This project demonstrates how to install, configure and use **Apache NiFi** inside a Docker container to build a simple data ingestion pipeline. NiFi reads CSV files from a local folder, processes them through a flow, and writes the results to an output folder. The goal is to show understanding of Big Data ingestion concepts and tooling.

---

## 2. Chosen tool: Apache NiFi

We chose **Apache NiFi** because:

- It is a **visual dataflow tool** adapted to Big Data architectures.
- It allows **easy ingestion, routing and transformation** of data from multiple sources.
- It integrates well with the Hadoop ecosystem (HDFS, Kafka, Hive, etc.).
- It is **easy to run with Docker**, which matches the constraints of the project.

---

## 3. Installation steps (Docker)

### 3.1 Prerequisites

- Docker installed
- Docker Compose installed
- Git installed

### 3.2 Clone the repository

```bash
git clone https://github.com/<votre-compte>/<votre-repo>.git
cd <votre-repo>
