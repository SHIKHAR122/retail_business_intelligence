Retail Business Intelligence Engine
Project Overview
The Retail Business Intelligence Engine is a structured SQL-based analytics system built to transform raw retail transaction data into actionable business insights. The project emphasizes clean schema design, data standardization, and modular analytics pipelines, enabling reproducible and scalable business intelligence workflows.
Dataset Description
Source: Sample Superstore dataset from Tableau Community
Format: CSV → SQLite database
Number of Records: 9,994
Key Columns:
order_id, order_date, ship_date, customer_id, customer_name
segment, region, category, sub_category, product_name
sales, quantity, discount, profit
Date Range: 2014-01-03 → 2017-12-30
Data Cleaning:
Standardized column names to snake_case
Converted dates to ISO format (YYYY-MM-DD)
Converted discount to REAL
Built a clean analytics-ready table: retail_clean
Project Architecture
Copy code

retail_bi_engine/
│
├── data/
│   ├── raw/                   # Original CSV dataset
│   └── processed/             # SQLite DB with clean data
│
├── schema/
│   └── schema.sql             # Clean table structure
│
├── modules/
│   └── module_1_data_cleaning/
│       ├── cleaning_queries.sql
│       └── documentation.md
│
└── README.md
Key Concepts:
Modules: Each module contains SQL scripts and documentation for a specific phase of the BI engine.
Separation of Concerns: Schema, transformation, and documentation are modular for clarity and reproducibility.
Data Validation: Row counts, date ranges, and column types are validated after cleaning.
Module 1 – Data Cleaning & Standardization
Objective: Transform raw retail dataset into analytics-ready format.
Tasks Performed:
Renamed original table: "Sample - Superstore" → retail
Created retail_clean table with:
Snake_case column names
Correct data types
ISO date format
REAL discount
Inserted data into retail_clean with transformations
Validated:
Row count = 9,994
Dates correctly formatted (YYYY-MM-DD)
Discount data type = REAL
Column naming consistency
Output: Clean, structured table ready for analytical modules.
Next Steps
Future modules will include:
Module 2 – Business KPI Engine: Total revenue, profit, margins, and regional/category breakdowns
Module 3 – Product Performance: Top products, contribution percentages, and Pareto analysis
Module 4 – Customer Value Analysis: Customer segmentation, top revenue contributors, and risk identification
Module 5 – Discount Sensitivity: Revenue and profit impact by discount bands

CREATED BY :-  **SHIKHAR SHARMA**
STATUS :-  **IN PROGRESS**
