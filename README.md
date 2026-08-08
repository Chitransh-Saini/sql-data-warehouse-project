# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a template/portfolio repository, it highlights industry best practices in data engineering and analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server Database.
2. **Silver Layer**: Cleanses, standardizes, and normalizes data to prepare it for detailed analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project encompasses:

1. **Data Architecture**: Designing a Modern Data Warehouse using Medallion Architecture (**Bronze**, **Silver**, and **Gold** layers).
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards to derive actionable business insights.

🎯 This repository provides a reference implementation for concepts in:
- SQL Development
- Data Architecture
- Data Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Essential Tools & Resources

- **[Datasets](datasets/):** Project datasets (CSV files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight database engine for hosting the data warehouse.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms):** Integrated environment for managing SQL infrastructure.
- **[Draw.io](https://www.drawio.com/):** Visual tool for designing architecture diagrams and data models.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to downstream ingestion.
- **Integration**: Combine both sources into a unified, user-friendly data model optimized for analytical queries.
- **Scope**: Focus on the latest snapshot dataset; historical tracking (SCD) is not required.
- **Documentation**: Provide clear documentation of the data model to support analytics and business stakeholders.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver actionable insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

---

## 📂 Repository Structure# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a template/portfolio repository, it highlights industry best practices in data engineering and analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server Database.
2. **Silver Layer**: Cleanses, standardizes, and normalizes data to prepare it for detailed analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project encompasses:

1. **Data Architecture**: Designing a Modern Data Warehouse using Medallion Architecture (**Bronze**, **Silver**, and **Gold** layers).
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards to derive actionable business insights.

🎯 This repository provides a reference implementation for concepts in:
- SQL Development
- Data Architecture
- Data Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Essential Tools & Resources

- **[Datasets](datasets/):** Project datasets (CSV files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight database engine for hosting the data warehouse.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms):** Integrated environment for managing SQL infrastructure.
- **[Draw.io](https://www.drawio.com/):** Visual tool for designing architecture diagrams and data models.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to downstream ingestion.
- **Integration**: Combine both sources into a unified, user-friendly data model optimized for analytical queries.
- **Scope**: Focus on the latest snapshot dataset; historical tracking (SCD) is not required.
- **Documentation**: Provide clear documentation of the data model to support analytics and business stakeholders.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver actionable insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

For detailed specifications, refer to [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure
