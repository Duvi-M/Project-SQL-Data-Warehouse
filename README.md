# SQL Data Warehouse Project (Personal Portfolio)

Welcome to my **SQL Data Warehouse Project** repository 🚀  
This is a **personal portfolio project** developed as part of an advanced SQL and Data Warehousing course. The goal of this project is to demonstrate my hands-on experience with SQL, ETL processes, data modeling, and analytical reporting.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach, organized into **Bronze**, **Silver**, and **Gold** layers:

- **Bronze Layer**: Raw data ingestion from source systems (CSV files).
- **Silver Layer**: Data cleansing, standardization, and transformation.
- **Gold Layer**: Business-ready data modeled using a **star schema** for analytics and reporting.

This layered approach improves data quality, scalability, and maintainability.

---

## 📖 Project Overview

The project covers the complete lifecycle of a modern data warehouse:

- Designing a data warehouse architecture
- Building ETL pipelines using SQL
- Cleaning and transforming raw data
- Creating fact and dimension tables
- Writing analytical queries for business insights

The final dataset supports analysis of:
- Customer behavior
- Product performance
- Sales trends

---

## 📚 What I Learned

Through this project, I strengthened my skills in:

- Advanced SQL querying
- Data cleansing and normalization techniques
- ETL development using SQL Server
- Star schema and dimensional data modeling
- Writing analytical SQL queries for reporting
- Organizing data projects using best practices

---

## 🛠️ Tools & Technologies

- **SQL Server / SQL Server Express**
- **SQL Server Management Studio (SSMS)**
- **CSV Data Sources (ERP & CRM)**
- **Draw.io** for architecture and data modeling diagrams
- **Git & GitHub** for version control

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/            # Raw datasets (ERP and CRM CSV files)
├── docs/                # Documentation and diagrams
├── scripts/             # SQL scripts for ETL and transformations
│   ├── bronze/          # Raw data ingestion
│   ├── silver/          # Data cleaning and transformations
│   ├── gold/            # Analytical models (fact & dimension tables)
├── tests/               # Data quality and validation scripts
├── README.md            # Project documentation
├── LICENSE
└── .gitignore
