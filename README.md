# 📊 Data Warehouse & Analytics Project

Welcome to the **Data Warehouse and Analytics Project**! 🚀  
This project showcases a complete end-to-end **data warehousing and analytics solution**—from ingesting raw data to delivering business-ready insights using SQL Server. Designed as a **professional portfolio project**, it demonstrates industry-standard practices in **data engineering**, **ETL pipeline design**, **data modeling**, and **analytics reporting**.

---

## 🏗️ Data Architecture

The data architecture follows the **Medallion Architecture** pattern:

![Data Architecture](docs/data_architecture.png)

### 🔸 Bronze Layer – *Raw Data Ingestion*
- Ingests raw CSV files (ERP and CRM sources).
- Loaded into SQL Server using `BULK INSERT`.
- No transformations are applied to preserve source integrity.

### 🔹 Silver Layer – *Data Cleaning & Transformation*
- Cleanses, standardizes, and integrates raw data.
- Applies business rules, resolves data quality issues, and prepares for analytics.

### 🟡 Gold Layer – *Business-Ready Data*
- Models data into a **Star Schema** using fact and dimension tables.
- Optimized for reporting, dashboards, and decision-making.

---

## 📖 Project Scope

This project covers the entire **data engineering lifecycle**:

1. ✅ **Data Architecture**  
   - Design based on Bronze, Silver, and Gold layers.

2. ⚙️ **ETL Pipelines**  
   - Extract → Transform → Load process using SQL scripts.

3. 🗂️ **Data Modeling**  
   - Design and implementation of **Star Schema** with Fact & Dimension tables.

4. 📈 **Analytics & Reporting**  
   - Generate SQL-based business insights and KPIs.

---

## 👨‍💼 Who This Project is For

This project is ideal for those targeting roles like:
- Data Engineer  
- ETL Developer  
- Data Architect  
- SQL Developer  
- Business Intelligence Analyst  

---


