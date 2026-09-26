# sql-data-warehouse-project
Welcome to **sql-data-warehouse-project** repo!!
A SQL data warehouse designed for efficient data reporting and analysis.
Features:  ETL pipeline to extract, clean, and transform data  
           Structured tables optimized for querying and reporting 
           Designed for business intelligence and data analytics

-------
           
## 📌 Project Requirements
### Data Sources
Import data from source systems provided as CSV files (e.g., ERP and CRM data).
### Data Quality
Cleanse and resolve data quality issues (duplicates, nulls, inconsistent formats) prior to analysis.
### Integration
Combine data from multiple sources into a single, user-friendly data model designed for analytical queries.
### Scope
Focus on the latest dataset only, historization of data is not required.
### Documentation
Provide clear documentation of the data model to support both business stakeholders and analytics teams.

------

## 🎯 Objectives
Building a modern data warehouse using SQL Server to consolidate sales/business data.
Implemented a layered architecture (Bronze, Silver, Gold) to separate raw, cleaned, and business-ready data.
Applying  ETL best practices:
                -extraction, transformation, and loading with data quality checks at each stage.
                -Designing a star schema  optimized for fast, intuitive reporting.
                -Enable stakeholders to make data-driven decisions through reliable, well-structured datasets.

-----
                
## 🛠️ Specifications
Layer	Purpose	Description
**Bronze Raw Layer**	Stores raw data as is from source systems. Data is ingested from CSV files into the SQL database with no transformations.
**Silver	Cleansed Layer**	Includes data cleansing, standardization, and normalization processes to prepare data for analysis.
**Gold Business Layer** 	Houses business ready data modeled into a star schema required for reporting and analytics.

----

## Technical details:
**Database**:  MySQL
**ETL Approach**: Batch processing, full load with truncate and insert
**Data Modeling**: Star schema 
**Tools**: Draw.io for data architecture and modeling diagrams
**Naming Conventions**: Consistent table and column naming standards using snake_case
**📊 BI**: Analytics & Reporting

The Gold layer is designed to directly support business intelligence and reporting needs, including:

**Customer Behavior** — analyzing purchasing patterns and customer segmentation
**Product Performance** — identifying top-performing and underperforming products
**Sales Trends** — tracking revenue, order volume, and growth over time

These insights empower stakeholders with key business metrics, enabling strategic decision making through dashboards,  SQL queries, or BI tool-power BI .

-----

## 👤 About Me

Hi, I'm Tripti — a data enthusiast learning and building projects in SQL, data engineering, and analytics.

This project is part of my journey into data warehousing and business intelligence, and I'm continuously improving my skills in ETL design, data modeling, and SQL development.

🔗 LinkedIn: [https://www.linkedin.com/in/tripti-g-c-0332b3408/?isSelfProfile=true]
💻 GitHub: [https://github.com/triptigc]
📧 Email: [triptigc3@gmail.com]
