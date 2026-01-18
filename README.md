# Pyspark with Delta Tables

## 📌 Overview
This project demonstrates how to build and manage **ETL pipelines using PySpark and Delta Lake**.  
It follows the **Medallion Architecture (Bronze → Silver → Gold layers)** to ensure clean, reliable, and analytics-ready data.

The repository includes **Jupyter notebooks**, sample **raw CSVs**, and Delta tables to illustrate end-to-end workflows such as ingestion, transformation, and enrichment.

---

## 📂 Project Structure

| Folder / File        | Description |
|----------------------|-------------|
| `data/raw_csvs`      | Sample raw CSV datasets used for ingestion (Bronze layer). |
| `delta`              | Delta tables generated during transformations (Silver/Gold layers). |
| `notebooks`          | Jupyter notebooks with PySpark code for ETL workflows. |
| `images`             | Diagrams or visuals explaining architecture and workflows. |
| `requirements.txt`   | Python dependencies required to run the project. |
| `README.md`          | Documentation for setup, usage, and contribution guidelines. |

---

## 🚀 Features
- Delta Lake integration: ACID transactions, schema enforcement, and time travel  
- Medallion Architecture: Structured data layers (Bronze, Silver, Gold)  
- PySpark transformations: Cleaning, joining, and enriching datasets  
- Jupyter notebooks: Step-by-step, reproducible workflows  
- Developer-friendly documentation: Clear guides for collaborators  

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.11 
- Apache Spark (with PySpark)  
- Delta Lake libraries  4.11
