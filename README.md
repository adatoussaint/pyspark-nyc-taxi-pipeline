# PySpark NYC Taxi Trip Pipeline

## Overview
End-to-end PySpark data engineering pipeline built on the NYC TLC Yellow Taxi Trip 
Record dataset (January 2026). This project demonstrates production-relevant data 
engineering skills including data cleaning, transformations, window functions, 
dimensional modeling, and Delta Lake output.

## Business Problem
NYC's Taxi & Limousine Commission collects millions of trip records monthly. 
This pipeline processes raw trip data to answer key operational questions:
- What are the busiest pickup locations and times?
- How do tips and fares vary by time of day and day of week?
- Which vendors have the highest average trip distance?

## Tech Stack
- **PySpark** — distributed data processing
- **Databricks Community Edition** — execution environment
- **Delta Lake** — output format
- **SQL** — dimensional model DDL
- **GitHub** — version control and portfolio

## Dataset
- Source: NYC TLC Trip Record Data
- File: Yellow Taxi Trip Records — January 2026 (PARQUET)
- Link: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Project Structure
```
pyspark-nyc-taxi-pipeline/
├── notebooks/        # PySpark transformation notebook
├── data/             # Data source instructions
├── diagrams/         # Architecture and star schema diagrams
├── sql/              # Star schema DDL scripts
└── README.md
```

## Key Skills Demonstrated
- PySpark DataFrame operations (filter, groupBy, agg, join, withColumn)
- Window functions (rank, row_number, lag)
- Null handling and schema enforcement
- Writing to Delta Lake format
- Kimball dimensional modeling (star schema)

## Status
🚧 In Progress — June 2026
