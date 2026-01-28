# SQL Data Warehouse Project

## 📌 Project Overview

This project demonstrates the design and implementation of a **modern SQL Server–based Data Warehouse** using best practices in **Data Engineering and Analytics**. The solution follows the **Medallion Architecture (Bronze, Silver, Gold layers)** to transform raw operational data into analytics-ready datasets that support business intelligence and reporting.

The project simulates real-world enterprise scenarios by integrating data from multiple source systems (ERP and CRM), performing data cleansing and transformations, and modeling data using a **star schema** for efficient querying.

---

## 🏗️ Architecture

The data warehouse is structured using the **Medallion Architecture**:

### 🔹 Bronze Layer (Raw Data)

* Ingests raw data from source systems (CSV files)
* Stores data with minimal transformation
* Acts as a historical and traceable data source

### 🔹 Silver Layer (Cleaned & Transformed Data)

* Performs data cleansing, standardization, and normalization
* Resolves data quality issues (nulls, duplicates, inconsistent formats)
* Prepares data for analytical modeling

### 🔹 Gold Layer (Analytics & Reporting)

* Implements business-ready data models
* Uses **star schema design** with fact and dimension tables
* Optimized for BI tools, dashboards, and analytical queries

---

## 📊 Data Modeling

* Designed **fact tables** to capture measurable business events (e.g., sales)
* Built **dimension tables** for descriptive attributes (customers, products, dates)
* Applied **dimensional modeling best practices** to improve query performance and usability

---

## 🔄 ETL / ELT Pipeline

* Extracted data from ERP and CRM source files
* Transformed data using SQL-based transformations
* Loaded data incrementally across Bronze, Silver, and Gold layers
* Ensured referential integrity between fact and dimension tables

---

## ✅ Data Quality & Validation

* Implemented validation checks to ensure:

  * Data completeness and consistency
  * Correct data types and formats
  * Accurate joins between entities
* Reduced downstream reporting errors by enforcing quality at the Silver layer

---

## 🛠️ Technologies Used

* **Database:** SQL Server
* **Languages:** SQL, T-SQL
* **Data Architecture:** Data Warehouse, Medallion Architecture
* **Modeling:** Star Schema, Dimensional Modeling
* **Data Engineering Concepts:** ETL, Data Cleansing, Data Quality Checks

---

## 📁 Project Structure

```
├── datasets/            # Source ERP & CRM CSV files
├── bronze/              # Raw ingestion scripts
├── silver/              # Cleansing & transformation scripts
├── gold/                # Analytics & star schema models
├── documentation/       # Architecture & data flow documentation
└── README.md            # Project overview
```

---

## 🎯 Key Outcomes

* Built an end-to-end **analytics-ready data warehouse**
* Demonstrated real-world **data engineering workflows**
* Enabled efficient analytical querying through optimized data models
* Created reusable, well-documented SQL pipelines

---

## 🚀 Future Enhancements

* Automate pipelines using orchestration tools (e.g., Airflow, Azure Data Factory)
* Add incremental load and change data capture (CDC)
* Integrate BI dashboards (Power BI / Tableau)
* Extend to cloud-based data warehouse solutions

---

## 📌 Use Case

This project is ideal for demonstrating skills relevant to:

* Data Engineer
* Analytics Engineer
* SQL / BI Developer
* Backend Engineer with data focus

---
## Contact me
Impressed :) reach out to me on my email pritambarua99@gmail.com

---

*This project was built for learning and portfolio purposes, following industry-aligned data engineering best practices.*
