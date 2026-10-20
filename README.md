
# Data Warehouse and Analytics Project

Building my skills in **SQL, Data Analytics, Data Warehousing, and Business Intelligence** through a hands-on SQL Server project.

[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/en-us/sql-server)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

## About This Project

This project focuses on building a modern data warehouse using **Microsoft SQL Server** by integrating raw data from two source systems: CRM and ERP.

The objective is to transform raw CSV files into clean, structured, and analysis-ready datasets that can support business reporting and decision-making.

I am using this project to strengthen my practical SQL skills, understand data warehouse architecture, implement ETL workflows, and develop a foundation for real-world data analytics.

**Project focus:** Data cleaning, data integration, dimensional modeling, SQL analytics, and business insights.

## About Me

Hi, I'm **Rahul Mishra**, a BCA graduate from IGNOU (2026) and an MIS Executive with experience in reporting, data validation, and operational data analysis.

In my current role, I work with operational datasets, validate information across multiple sources, investigate discrepancies, and use Excel functions to support accurate reporting and management review.

I am transitioning toward **Data Analytics**, building on my existing experience with business data and developing stronger technical skills in SQL, Python, Excel, and Business Intelligence tools.

My goal is to combine practical business understanding with technical analysis to solve real-world problems and deliver actionable insights.

### My Current Skill Set

- **SQL:** Querying, filtering, joins, aggregations, data validation, and analytical queries.
- **Microsoft Excel:** Advanced formulas, lookups, filtering, data cleaning, and reporting.
- **Python:** Learning data manipulation and analysis with Pandas and related libraries.
- **Business Intelligence:** Learning Power BI and dashboard development.
- **Data Warehousing:** Learning ETL processes, layered architecture, and dimensional modeling.
- **Tools:** SQL Server, SQL Server Management Studio (SSMS), Git, and GitHub.

## Project Objectives

### 1. Data Warehouse Development

Build a modern data warehouse using SQL Server to consolidate sales data from CRM and ERP source systems.

**Requirements:**

- Import six source CSV files from the provided CRM and ERP datasets.
- Organize the warehouse into Bronze, Silver, and Gold layers.
- Clean, standardize, and validate the source data.
- Integrate related entities across source systems.
- Design a business-friendly data model.
- Document the architecture, transformations, and data model.

### 2. Data Analytics

Use SQL to explore the curated datasets and investigate business questions related to:

- Customer behavior and purchasing patterns.
- Product performance and sales contribution.
- Sales trends and changes over time.
- Data quality and consistency.
- Business metrics that support better decision-making.

The aim is to move beyond writing queries and understand how data can be translated into meaningful business insights.

## Data Architecture

This project follows the **Medallion Architecture**, separating data processing into three layers.

![Data Architecture](02_docs/data_architecture.png)

### Bronze Layer — Raw Data

- Load source CSV files into SQL Server.
- Preserve the original source structure.
- Establish a consistent ingestion process.
- Maintain traceability to the original datasets.

### Silver Layer — Cleaned Data

- Standardize data formats and values.
- Handle missing and inconsistent data.
- Resolve data quality issues.
- Apply transformations and validation rules.
- Prepare integrated datasets for analysis.

### Gold Layer — Business-Ready Data

- Build analytical tables using dimensional modeling.
- Organize data into fact and dimension tables.
- Implement a star schema where appropriate.
- Prepare datasets for reporting and business analysis.

## Project Structure

```text
sql-data-warehouse-project/
│
├── 00_setup/
│   └── Setup instructions and environment configuration
│
├── 01_datasets/
│   ├── source_crm/
│   └── source_erp/
│
├── 02_docs/
│   ├── requirements.md
│   ├── data_architecture.png
│   └── Data model and project documentation
│
├── 03_scripts/
│   ├── init_database.sql
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
└── 04_tests/
    └── Data quality and validation checks
```

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft SQL Server | Database and data warehouse development |
| SQL Server Management Studio (SSMS) | Writing and executing SQL scripts |
| SQL | Data transformation, validation, and analytics |
| Git and GitHub | Version control and project documentation |
| draw.io | Architecture and data model diagrams |
| Excel | Supporting data inspection and validation |
| Power BI | Business intelligence and dashboard development |

## Key Learning Areas

Through this project, I am working on the following concepts:

- Designing a layered data warehouse.
- Loading raw CSV data into a relational database.
- Writing reusable SQL scripts and stored procedures.
- Implementing data cleaning and standardization rules.
- Integrating data from multiple source systems.
- Designing fact tables, dimension tables, and star schemas.
- Validating data quality before analytical reporting.
- Writing SQL queries to answer business questions.
- Documenting technical workflows and business requirements.

## Getting Started

### Prerequisites

- Microsoft SQL Server.
- SQL Server Management Studio (SSMS).
- Git.
- The source CSV files included in the repository.

### Setup

1. Clone or download the repository.
2. Follow the instructions in the `00_setup` directory.
3. Configure the database and source file paths.
4. Execute `03_scripts/init_database.sql`.
5. Run the Bronze, Silver, and Gold scripts in the documented order.
6. Execute the validation scripts in `04_tests`.
7. Run analytical SQL queries against the Gold layer.

The original project scripts expect the source files under:

```text
C:\sql\dwh_project\01_datasets\
```

Update the paths in `03_scripts/bronze/proc_load_bronze.sql` if your datasets are stored elsewhere.

For the complete setup instructions, refer to the project's `00_setup` directory.

## Resources

- **SQL Server:** https://www.microsoft.com/en-us/sql-server
- **SQL Server Management Studio:** https://learn.microsoft.com/en-us/ssms/
- **Git:** https://git-scm.com/
- **GitHub:** https://github.com/
- **draw.io:** https://www.drawio.com/
- **Power BI:** https://powerbi.microsoft.com/
- **Python:** https://www.python.org/

## Project Reference and Attribution

This project is based on the educational materials and implementation approach provided by **Baraa Khatib Salkini (Data With Baraa)**.

- **Original repository:** https://github.com/DataWithBaraa/sql-data-warehouse-project
- **YouTube channel:** https://www.youtube.com/@datawithbaraa
- **Project walkthrough:** https://youtu.be/9GVqKuTVANE
- **Project requirements:** `02_docs/requirements.md`

The original project provides the source datasets, scripts, setup instructions, and documentation. My focus is on learning the underlying concepts, understanding the implementation, and documenting my own analysis and improvements.

Original project materials are distributed under the MIT License. Please refer to the original repository and its license for attribution and reuse requirements.

## Connect With Me

I'm interested in Data Analytics, SQL, Business Intelligence, and opportunities to solve practical business problems through data.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahulmishra25/)

**Rahul Mishra**  
BCA Graduate | MIS Executive | Aspiring Data Analyst

