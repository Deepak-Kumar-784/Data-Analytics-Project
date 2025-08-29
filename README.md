# Data Analytics Project

Welcome to the **Data Analytics Project** repository! 🚀  
This project demonstrates comprehensive data analytics solutions using SQL Server, SQL queries, and reporting. It highlights skills in data processing, transformation, and visualization, ideal for portfolio showcases.

---

## 🏗️ Data Architecture

The project follows a structured data processing workflow:

![Data Architecture](docs/data_architecture.png)

1. **Raw Data**: Imported from CSV files into SQL Server for initial storage.
2. **Transformed Data**: Data is cleaned, standardized, and prepared for analysis.
3. **Analytics Layer**: Data is modeled into fact and dimension tables optimized for reporting.

---

## 📖 Project Overview

This repository includes:

1. **Data Extraction & Loading**: Importing raw data from CSV files into SQL Server.
2. **ETL Processes**: Transforming data to prepare it for analysis.
3. **Data Modeling**: Creating tables for analytical queries.
4. **Analytics & Reporting**: Generating insights from SQL queries and visualizations.

🎯 The project demonstrates expertise in:

- SQL Development
- Data Analysis
- Data Modeling
- ETL Pipelines
- Reporting & Dashboards

---

## 🛠️ Important Links & Tools

- **[Datasets](datasets/):** CSV files used for analysis.
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Database server for hosting data.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI to manage databases and run queries.
- **[GitHub](https://github.com/):** Version control and collaboration.
- **[DrawIO](https://www.drawio.com/):** Create data flow and architecture diagrams.

---

## 🚀 Project Requirements

### Data Processing & Analysis

#### Objective

Perform SQL-based analytics to extract meaningful insights from datasets, focusing on:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

#### Specifications

- Import data from CSV files.
- Clean and normalize the data.
- Build fact and dimension tables for analytical queries.
- Provide SQL scripts for reporting and visualization.

---

## 📂 Repository Structure

```
Data-analytics-project/
│
├── datasets/                           # Project datasets (bronze = raw, silver = cleaned, gold = curated)
│   ├── DataWarehouseAnalytics.bak      # Backup of warehouse project
│   └── csv-files/                      # Layered CSV data
│       ├── bronze.*.csv                # Raw ERP & CRM input data
│       ├── silver.*.csv                # Transformed / cleaned datasets
│       └── gold.*.csv                  # Final curated dimensional & fact tables
│
├── docs/                               # Project documentation
│   ├── Project Roadmap.pdf             # Roadmap document
│   └── Project Roadmap.png             # Roadmap diagram
│
├── scripts/                            # SQL scripts for ETL and analytics
│   ├── 00_init_database.sql            # Initialization of database schema
│   │
│   ├── Advanced Data Analysis scripts/ # SQL scripts for advanced analytics
│   │   ├── 06_ranking_analysis.sql
│   │   ├── 07_change_over_time_analysis.sql
│   │   ├── 08_cumulative_analysis.sql
│   │   ├── 09_performance_analysis.sql
│   │   ├── 10_data_segmentation.sql
│   │   ├── 11_part_to_whole_analysis.sql
│   │   ├── 12_report_customers.sql
│   │   └── 13_report_products.sql
│   │
│   └── Exploratory Data Analysis scripts/ # SQL scripts for exploration
│       ├── 01_database_exploration.sql
│       ├── 02_dimensions_exploration.sql
│       ├── 03_date_range_exploration.sql
│       ├── 04_measures_exploration.sql
│       └── 05_magnitude_analysis.sql
│
├── .gitignore                          # Files and directories to be ignored by Git
├── LICENSE                             # License information for the repository
└── README.md                           # Project overview and instructions
```

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.
