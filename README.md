# ETL Data Pipeline using Pentaho (Spoon)

This project demonstrates an **end-to-end ETL (Extract, Transform, Load) pipeline** built using **Pentaho Data Integration (Spoon)**.
The objective of this project is to process **multi-source transactional data**, clean and transform it, and prepare it for further analysis in **SQL Server**.

In real-world businesses, data often comes from multiple sources and formats. This project simulates that scenario by integrating different data sources and transforming them into a structured dataset that can be used for analytics and reporting.

---

# Project Objective

The main objective of this project is to:

* Extract raw data from multiple file formats
* Clean and standardize inconsistent data
* Handle missing or invalid values
* Transform the data into a structured format
* Load the processed data into SQL tables for analysis

This pipeline demonstrates how **raw business data is converted into analysis-ready datasets**, which is a crucial step in the data analytics workflow.

---

# Data Sources

The project uses multiple types of data sources to simulate a real-world data environment.

* **Excel files** – Banks, Merchants
* **CSV files** – Accounts, Fraud Flags
* **JSON files** – Cities, Transaction Fees
* **XML files** – Customers, Transactions
* **SQL scripts** – Categories, Payment Methods

Each data source represents different entities involved in a financial transaction system.

---

# ETL Pipeline Steps

The following transformations were performed in the ETL pipeline:

### 1. Data Extraction

Data was extracted from multiple file formats including Excel, CSV, JSON, XML, and SQL scripts.

### 2. Data Cleaning

String operations were applied to clean inconsistent data such as unwanted spaces or formatting issues.

### 3. Handling Missing Values

Null values and incomplete records were handled to maintain data quality.

### 4. Data Transformation

Value mapping and filtering techniques were used to standardize and categorize the data.

### 5. Data Sorting and Structuring

The datasets were sorted and structured to maintain consistency and improve usability.

### 6. Data Loading

The final cleaned dataset will be loaded into **SQL Server tables** for further analysis.

---

# ETL Pipeline Workflow

Below is the transformation workflow created in **Pentaho Spoon**.

![ETL Pipeline Workflow](Screenshot%202026-03-15%20150400.png)

---

# Tools & Technologies Used

* Pentaho Data Integration (Spoon)
* SQL
* ETL Pipelines
* Data Cleaning
* Data Transformation

---

# Future Work

The next phase of this project includes:

* Loading the transformed data into **SQL Server**
* Designing an **ER Diagram** to define table relationships
* Performing **analytical SQL queries**
* Building a **Power BI dashboard** for business insights

---

# Project Outcome

* Built a complete **ETL pipeline using Pentaho**
* Gained hands-on experience in **data transformation workflows**
* Prepared multi-source data for **analytics and reporting**


![ETL Pipeline Workflow](Screenshot%202026-03-15%20150400.png)
