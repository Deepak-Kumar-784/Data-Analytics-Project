# Data Analytics Project

Welcome to the **Data Analytics Project** repository! 🚀  
This project demonstrates comprehensive data analytics solutions using SQL Server, SQL queries, and reporting. It highlights skills in data processing, transformation, and visualization, ideal for portfolio showcases.

---

## 🏗️ Data Architecture

The project follows a structured data processing workflow:

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
├── README.md                           # Project overview and instructions
├── Advanced Data Analytics.docx        # Detailed analysis documentation and insights
└── DataWarehouseAnalytics.docx         # Data warehouse architecture and schema documentation
```

---

## 📋 Additional Files

- **Advanced Data Analytics.docx**: Comprehensive documentation containing detailed analysis, insights, and findings from the data analytics project.
- **DataWarehouseAnalytics.docx**: Architecture and schema documentation describing the data warehouse design, ETL processes, and data model.

_Note: These Word documents are excluded from version control (see `.gitignore`) to keep the repository lightweight. Store backups separately._

---

## 📌 .gitignore Configuration

The `.gitignore` file is configured to exclude the following file types from version control:

```gitignore
*.docx  # Microsoft Word documents (reduces repository size due to binary format)
*.pdf   # PDF files (documentation backups)
```

**Rationale**: These files are typically large and binary, making them difficult to track efficiently in Git. It's recommended to maintain separate backups of important documentation.

---

## 🚀 Getting Started

### Prerequisites

- **SQL Server Express** or higher (download from [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads))
- **SQL Server Management Studio (SSMS)** (download from [Microsoft SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16))
- **Git** for version control

### Setup Instructions

1. **Clone the repository**:

   ```powershell
   git clone https://github.com/Deepak-Kumar-784/Data-Analytics-project.git
   cd Data-Analytics-project
   ```

2. **Create the database**:

   - Open SQL Server Management Studio (SSMS)
   - Connect to your SQL Server instance
   - Execute the script: `scripts/00_init_database.sql`

3. **Load data**:

   - Import CSV files from `datasets/csv-files/` into their respective tables using SSMS data import tools

4. **Run analysis queries**:
   - Execute scripts from `scripts/Exploratory Data Analysis scripts/` for initial exploration
   - Execute scripts from `scripts/Advanced Data Analysis scripts/` for detailed insights

---

## 📚 SQL Script Organization

### Exploratory Data Analysis (EDA)

- **01_database_exploration.sql**: Overview of database structure, tables, and relationships
- **02_dimensions_exploration.sql**: Analysis of dimension tables (customers, products, locations)
- **03_date_range_exploration.sql**: Date range, temporal distribution, and time period analysis
- **04_measures_exploration.sql**: Analysis of fact measures (sales, quantities, amounts)
- **05_magnitude_analysis.sql**: Distribution analysis, magnitude scaling, and statistical measures

### Advanced Analytics

- **06_ranking_analysis.sql**: Top products, best customers, ranking and leaderboard queries
- **07_change_over_time_analysis.sql**: Trend analysis, year-over-year (YoY) comparisons, and growth rates
- **08_cumulative_analysis.sql**: Cumulative sum, running totals, and growth accumulation
- **09_performance_analysis.sql**: Performance metrics, KPIs, efficiency measures, and benchmarks
- **10_data_segmentation.sql**: Customer segmentation, RFM analysis, product segmentation
- **11_part_to_whole_analysis.sql**: Composition analysis, contribution percentage, market share
- **12_report_customers.sql**: Customer reports, demographics, purchase history, behavior analysis
- **13_report_products.sql**: Product reports, sales performance, inventory status, category analysis

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.
