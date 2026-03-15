# ETL-Data-Pipeline-Pentaho
End-to-End ETL Pipeline using Pentaho (Spoon) to process multi-source transactional data and load it into SQL for analysis.

# ETL Data Pipeline using Pentaho (Spoon)

This project demonstrates an end-to-end ETL pipeline built using Pentaho Data Integration (Spoon) to process multi-source transactional data.

## Data Sources
- Excel (Banks, Merchants)
- CSV (Accounts, Fraud Flags)
- JSON (Cities, Transaction Fees)
- XML (Customers, Transactions)
- SQL scripts (Categories, Payment Methods)

## ETL Steps
- Extract data from multiple sources
- Perform string operations for data cleaning
- Handle missing values
- Apply value mapping
- Filter invalid records
- Sort and structure datasets
- Load processed data into SQL tables

## Next Steps
The transformed data will be loaded into SQL Server where an ER diagram will be created and analytical SQL queries will be performed.

## ETL Pipeline Workflow

![ETL Pipeline Workflow](Screenshot%202026-03-15%20150400.png)

## Project Structure

ETL-Data-Pipeline-Pentaho
│
├── Internship Transformation.ktr
├── README.md
├── Screenshot.png

## Tools Used
Pentaho (Spoon)  
SQL (MySQL)  
Data Cleaning  
ETL Pipelines

## Future Work

- Load transformed data into SQL Server
- Design ER Diagram for database schema
- Perform analytical SQL queries
- Build Power BI dashboard for insights
