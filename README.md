# Business Intelligence & Data Warehouse Project

A modern SQL Server data warehouse project that consolidates CRM and ERP data into a single source of truth for business intelligence, reporting, and data-driven decision-making.

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-Database-blue?style=for-the-badge)
![Data Warehouse](https://img.shields.io/badge/Data%20Warehouse-Medallion%20Architecture-orange?style=for-the-badge)
![ETL](https://img.shields.io/badge/ETL-Bronze%20%7C%20Silver%20%7C%20Gold-green?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-Analytics-purple?style=for-the-badge)
![Draw.io](https://img.shields.io/badge/Draw.io-Diagrams-orange?style=for-the-badge)
![Notion](https://img.shields.io/badge/Notion-Documentation-black?style=for-the-badge)

---

## Project Overview

This project demonstrates the design and implementation of a modern SQL Server data warehouse using the **Medallion Architecture (Bronze, Silver, and Gold)**.

The solution integrates CRM and ERP datasets, cleans and standardises raw data, and transforms it into business-ready datasets that support reporting, analytics, and informed business decisions.

Alongside the technical implementation, the project includes architecture diagrams, data modelling, ETL documentation, and project documentation created using **Draw.io** and **Notion**, following industry best practices.

---

# Project Requirements

## Building the Data Warehouse

### Objective

Develop a modern SQL Server data warehouse that consolidates data from multiple business systems into a reliable reporting solution.

### Specifications

* Import CRM and ERP datasets from CSV files
* Clean and resolve data quality issues
* Integrate multiple data sources into a unified model
* Design a business-friendly dimensional data model
* Build a reporting layer for analytics
* Produce technical and business documentation

---

# Business Intelligence & Analytics

## Objective

Create SQL-based analytical datasets to provide business insights into:

* Customer Behaviour
* Product Performance
* Sales Trends

These datasets enable stakeholders to make informed, data-driven business decisions through accurate reporting and analysis.

---

# Technologies & Tools

### Database

* SQL Server
* SQL Server Management Studio (SSMS)
* T-SQL

### Data Engineering

* ETL
* Data Warehousing
* Medallion Architecture
* Data Cleaning
* Data Transformation
* Data Integration

### Data Modelling

* Star Schema
* Fact & Dimension Tables

### Documentation

* Draw.io (Architecture & Data Flow Diagrams)
* Notion (Project Planning & Documentation)

---

# Features

* Import CRM and ERP datasets
* Bronze, Silver, and Gold architecture
* Data cleansing and standardisation
* Business-ready reporting layer
* Dimensional data modelling
* SQL-based analytics
* Data lineage documentation
* High-level architecture diagrams
* Business documentation
* Naming conventions and best practices

---

# Project Workflow

1. Understand business reporting requirements
2. Design the data warehouse architecture
3. Load raw CRM and ERP data
4. Clean and standardise datasets
5. Transform data into business-ready structures
6. Design Star Schema
7. Create analytical reporting views
8. Document the complete solution

---

# Business Value

This project demonstrates how data from multiple operational systems can be transformed into a single, trusted source for reporting and analytics.

The solution improves:

* Data consistency
* Reporting accuracy
* Business visibility
* Decision-making
* Data quality
* Analytics readiness

---

# What I Learned

Through this project I strengthened my understanding of:

* SQL Server Development
* ETL Processes
* Data Warehousing
* Business Intelligence
* Star Schema Design
* Data Modelling
* Data Quality Management
* Technical Documentation
* Business-focused Reporting
* Translating business requirements into analytical solutions

---

# Future Improvements

Potential future enhancements include:

* Incremental data loading
* Automated ETL scheduling
* Power BI dashboard integration
* Historical data support
* Data quality validation framework
* Role-based security
* Cloud deployment using Azure

---

# How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/business-intelligence-data-warehouse.git
```

2. Open SQL Server Management Studio.

3. Execute the SQL scripts in the following order:

```
init_database.sql
ddl_bronze.sql
ddl_silver.sql
ddl_gold.sql
proc_load_bronze.sql
proc_load_silver.sql
```

4. Query the Gold layer views to analyse customer behaviour, product performance, and sales trends.

---

# Repository Structure

```
datasets/
scripts/
documentation/
tests/
drawio/
notion/
README.md
```

---

# Documentation

Project documentation includes:

* High-Level Architecture
* Data Flow Diagram
* Data Lineage
* Star Schema
* Data Model
* Business Context
* Naming Conventions
* ETL Design
* Integration Model

Documentation was created using **Draw.io** and **Notion**.

---

# License

This project is licensed under the MIT License. You are free to use, modify, and share this project with appropriate attribution.

---

# About Me

Hi, I'm **Priya Rithadia** 👋

I'm an aspiring **Business Analyst** with a strong interest in Business Intelligence, Data Analytics, and Process Improvement.

I hold an MSc in Engineering Business Management from the University of Warwick and have professional experience working with business processes, SQL, reporting, stakeholder collaboration, and cross-functional teams across the UK and India.

This repository showcases how I combined SQL, data warehousing, documentation, and business analysis concepts to build an end-to-end solution that transforms raw business data into meaningful insights for decision-making.
