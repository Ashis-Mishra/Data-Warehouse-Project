

# 📊 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics Project** repository!
This project showcases the end-to-end development of a modern data warehouse and analytics solution using industry-standard practices. It covers everything from raw data ingestion to insightful reporting using SQL Server and the Medallion Architecture.

---

## 🧱 Project Highlights

This project includes:

* **Data Modeling**: Star schema with fact and dimension tables.
* **ETL Pipelines**: Bronze, Silver, and Gold layers built using SQL.
* **Analytics & Reporting**: Actionable insights into sales, customer behavior, and product performance.
* **Documentation**: Well-documented data flows, models, and naming standards.

---

## 🏗️ Medallion Architecture

The project follows the **Medallion Architecture** with three distinct layers:

📂 **Bronze Layer**
Raw data ingestion from CSV files into SQL Server (ERP & CRM systems).

🧹 **Silver Layer**
Data cleaning, deduplication, and standardization for analysis-readiness.

📊 **Gold Layer**
Business-friendly, analytical star schema optimized for BI and reporting.



---

## ⚙️ Tech Stack & Tools

* **Database**: SQL Server Express
* **ETL & Modeling**: SQL Scripts (T-SQL)
* **Diagramming**: Draw\.io for architecture and data flows
* **Documentation**: Markdown and Notion
* **Data Source**: Simulated ERP & CRM CSV files

---

## 📈 Business Use Case

This solution enables:

* Unified view of customers and products from multiple systems
* Deeper understanding of **sales performance**, **customer trends**, and **product effectiveness**
* Reliable, report-ready datasets for BI teams

---

## 📁 Repository Structure

```
data-warehouse-project/
│
├── datasets/             # Raw ERP & CRM CSV files
├── docs/                 # Architecture diagrams, data catalog, flowcharts
├── scripts/              # SQL scripts for each pipeline layer
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/                # Data quality and validation checks
├── README.md             # Project overview
├── .gitignore
```

---

## ✅ Project Objectives

### 🔨 Data Engineering

* Ingest ERP & CRM data from CSVs into SQL Server
* Clean and transform data to address inconsistencies
* Integrate data into a unified model

### 📊 Data Analytics

* Analyze customer segmentation, product categories, and sales trends
* Build SQL queries for reporting and decision support
* Enable insight-driven business strategies

---

## 📌 Getting Started

1. Clone the repository
2. Set up SQL Server Express and SSMS
3. Import CSVs from `/datasets` into your database
4. Run the ETL scripts from `/scripts`
5. Explore the analytical outputs in the `gold` layer

---

## 📄 Documentation

* [Data Catalog](docs/data_catalog.md)
* [Data Architecture & Flow Diagrams](docs/)
* [Naming Conventions](docs/naming-conventions.md)
* [Project Tasks & Phases (Notion)](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4)

---

## 🤝 Acknowledgements

Inspired by real-world data engineering and BI practices, this project is a learning resource for:

* Aspiring Data Engineers
* BI Analysts
* SQL Developers
* Portfolio Builders

---

## 📬 Contact

Have questions or feedback? Feel free to reach out or fork the repo to contribute!

---
