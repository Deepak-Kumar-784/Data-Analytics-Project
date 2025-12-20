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
Data-Analytics-project/
│
├── datasets/                           # Project datasets (bronze = raw, silver = cleaned, gold = curated)
│   ├── DataWarehouseAnalytics.bak      # Backup of warehouse project
│   └── csv-files/                      # Layered CSV data
│       ├── bronze.*.csv                # Raw ERP & CRM input data
│       ├── silver.*.csv                # Transformed / cleaned datasets
│       └── gold.*.csv                  # Final curated dimensional & fact tables
│
├── docs/                               # Project documentation
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
└── (Word/PDF docs are not tracked; see .gitignore)
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
   - Caution: This script drops and recreates the `DataWarehouseAnalytics` database. Ensure you have backups before running.

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

---

## 🔧 Technologies & Skills Demonstrated

| Technology            | Purpose                        | Skills                                   |
| --------------------- | ------------------------------ | ---------------------------------------- |
| **SQL Server**        | Data storage and querying      | Database management, T-SQL               |
| **T-SQL**             | Data transformation & analysis | Window functions, CTEs, advanced queries |
| **ETL**               | Data pipeline processing       | Data cleaning, normalization, staging    |
| **Data Modeling**     | Fact & dimension tables        | Star schema, dimensional modeling        |
| **Power Query/Excel** | Data import & validation       | Data quality checks, transformation      |
| **Git**               | Version control                | Collaboration, code management           |

---

## 📊 Data Model Overview

### Core Entities

**Dimension Tables:**

- **dim_customers**: Customer information (ID, name, location, demographics)
- **dim_products**: Product catalog (ID, name, category, pricing)
- **dim_locations**: Geographic information (location ID, address, region)

**Fact Tables:**

- **fact_sales**: Sales transactions (customer ID, product ID, date, quantity, amount)

### Data Flow

```
Raw Data (Bronze Layer)
    ↓
Data Cleaning & Transformation (Silver Layer)
    ↓
Curated Analytics Data (Gold Layer)
    ↓
Dimensional & Fact Tables
    ↓
Analytics & Reports
```

---

## 💡 Key Insights & Use Cases

This project enables analysis of:

1. **Customer Analytics**

   - Customer segmentation (RFM analysis)
   - Purchase patterns and behavior
   - Customer lifetime value
   - Geographic distribution

2. **Product Performance**

   - Best/worst performing products
   - Category-wise sales analysis
   - Product trends over time
   - Price sensitivity analysis

3. **Sales Trends**

   - Monthly/quarterly/yearly comparisons
   - Seasonal patterns
   - Growth rates and forecasts
   - Top selling products by region

4. **Business Metrics**
   - Total revenue and margins
   - Average order value (AOV)
   - Customer acquisition cost (CAC)
   - Return on investment (ROI)

---

## 📈 Sample Analysis Examples

### Example 1: Top 10 Customers by Revenue

```sql
SELECT TOP 10 CustomerID, CustomerName, SUM(SalesAmount) as TotalRevenue
FROM fact_sales fs
JOIN dim_customers dc ON fs.CustomerID = dc.CustomerID
GROUP BY fs.CustomerID, dc.CustomerName
ORDER BY TotalRevenue DESC;
```

### Example 2: Monthly Sales Trend

```sql
SELECT DATETRUNC(MONTH, SalesDate) as Month, SUM(SalesAmount) as MonthlySales
FROM fact_sales
GROUP BY DATETRUNC(MONTH, SalesDate)
ORDER BY Month;
```

Note: `DATETRUNC` requires SQL Server 2022 or later. For older versions, use `DATEFROMPARTS(YEAR(SalesDate), MONTH(SalesDate), 1)`.

### Example 3: Product Performance by Category

```sql
SELECT Category, Product, SUM(Quantity) as TotalQty, SUM(SalesAmount) as Revenue
FROM fact_sales fs
JOIN dim_products dp ON fs.ProductID = dp.ProductID
GROUP BY Category, Product
ORDER BY Category, Revenue DESC;
```

---

## 📋 Dataset Information

### Datasets Included

| Layer      | Files       | Purpose                       | Record Count     |
| ---------- | ----------- | ----------------------------- | ---------------- |
| **Bronze** | 6 CSV files | Raw data from ERP/CRM systems | ~10,000+ records |
| **Silver** | 6 CSV files | Cleaned and standardized data | ~10,000+ records |
| **Gold**   | 5 CSV files | Curated dimensions and facts  | ~5,000+ records  |

### Data Quality Considerations

- **Completeness**: All required fields populated
- **Accuracy**: Data validated against source systems
- **Consistency**: Standardized formats and naming conventions
- **Uniqueness**: Primary keys ensure no duplicates
- **Timeliness**: Data current as of the processing date

---

## ⚙️ Performance Tips & Best Practices

### SQL Optimization

1. **Use Indexes**: Create indexes on frequently queried columns (foreign keys, dates)

   ```sql
   CREATE INDEX idx_sales_customer ON fact_sales(CustomerID);
   CREATE INDEX idx_sales_date ON fact_sales(SalesDate);
   ```

2. **Use CTEs**: Common Table Expressions for readability

   ```sql
   WITH CustomerMetrics AS (
       SELECT CustomerID, COUNT(*) as PurchaseCount
       FROM fact_sales
       GROUP BY CustomerID
   )
   SELECT * FROM CustomerMetrics WHERE PurchaseCount > 5;
   ```

3. **Window Functions**: Efficient ranking and cumulative calculations
   ```sql
   SELECT *, ROW_NUMBER() OVER (PARTITION BY CategoryID ORDER BY Sales DESC) as Rank
   FROM dim_products;
   ```

### Database Maintenance

- Regular backups of `DataWarehouseAnalytics.bak`
- Monitor query execution plans
- Archive old data periodically
- Update statistics for accurate query optimization

---

## ❓ Troubleshooting & FAQ

### Common Issues

**Q: "Cannot find database" error when running scripts**

- A: Ensure SQL Server is running and the database has been created via `00_init_database.sql`

**Q: CSV import fails with encoding issues**

- A: Ensure CSV files are UTF-8 encoded. Use SSMS Import/Export wizard with appropriate code page settings

**Q: Queries run slowly**

- A: Check if indexes exist. Execute `scripts/00_init_database.sql` (includes index creation) or create recommended indexes manually (see Performance Tips)

**Q: Data doesn't match expectations**

- A: Verify data is loaded in correct order: bronze → silver → gold. Check data in each layer

**Q: Permission denied when creating tables**

- A: Ensure you have appropriate SQL Server permissions (db_owner role)

### Performance Troubleshooting

- In SSMS, use Estimated/Actual Execution Plans to review query performance
- Use `SET STATISTICS IO, TIME ON` to measure I/O and timing
- Avoid SELECT \* when possible; specify required columns
- Use NOLOCK hints for read-only queries to reduce locks

---

## 👨‍💼 Author & Contact

**Author**: Deepak Kumar Behera

- **GitHub**: [Deepak-Kumar-784](https://github.com/Deepak-Kumar-784)
- **Email**: Contact via GitHub profile
- **Portfolio**: Check GitHub profile for more projects

Feel free to reach out for questions, feedback, or collaboration opportunities!

---

## 📝 Version History

| Version | Date     | Changes                                                |
| ------- | -------- | ------------------------------------------------------ |
| 1.0     | Dec 2025 | Initial project setup with comprehensive documentation |

---

## 🙏 Acknowledgments

- SQL Server documentation and best practices
- Data analytics community resources
- Open-source tools and libraries

---

## 📞 Support & Questions

If you encounter any issues or have questions:

1. Check the **Troubleshooting & FAQ** section above
2. Review the documentation in `docs/` folder
3. Examine existing SQL scripts for patterns and examples
4. Open an issue on GitHub with detailed information

---

**Happy analyzing! 📊✨**
