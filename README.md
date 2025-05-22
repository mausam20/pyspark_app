# Apple Products ETL Pipeline (Databricks + PySpark)

## Overview

This Databricks PySpark application performs an ETL (Extract, Transform, Load) process on Apple products data. The pipeline reads raw CSV data, transforms it by cleaning and structuring, and then writes the processed data to a target storage in different structured format.

## Features

- Built using PySpark in Databricks
- Extracts raw Apple product data from CSV files
- Cleans, filters, and transforms data for analytics
- Stores output in desired format for efficient querying

## Technologies Used

- **Databricks**
- **Apache Spark (PySpark)**
- **Delta Lake / Parquet (optional based on config)**
- **DBFS (Databricks File System)**

## ETL Steps

1. **Extract**  
   Reads Apple product data from CSV files and stored in DBFS

2. **Transform**  
  Performed required transformations and actions to get the required dataframe

3. **Load**  
Writes the cleaned data to a specified DBFS location in Parquet format or CSV or in delta tables
