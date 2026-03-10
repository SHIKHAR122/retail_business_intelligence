# 📊 Retail Business Intelligence (Retail BI)

## Project Overview

This project is a structured Retail Business Intelligence system built using SQL to transform raw transactional data into layered business insights.

The objective is to simulate real-world BI development through a staged analytical build:

* Data Cleaning
* Revenue and Profit Aggregation
* Segment-Level Growth Analysis
* Performance Benchmarking
* Time-Series Evaluation
* Revenue Contribution and Distribution Modeling
* Customer Behavioral Intelligence
* Product Performance Intelligence
* Advanced Analytical Insights

All analysis is modular, documented, and designed to reflect practical BI workflows used in modern analytics environments.

---

# Business Questions Answered

This BI system answers several important retail analytics questions.

## Revenue & Profitability

* Which product categories generate the most revenue?
* Which categories produce the highest profit margins?
* Are there categories with high sales but low profitability?
* Which sub-categories operate at a loss?

## Regional Performance

* Which regions generate the highest revenue?
* Which regions produce the highest profit margins?
* Where do revenue and profitability diverge?

## Customer Segmentation

* Who are the highest value customers?
* Which customers generate the highest lifetime revenue?
* Which customers purchase frequently?
* Which customers are at risk of churn?

## Growth & Trend Analysis

* How does revenue evolve month to month?
* Which customer segments are growing the fastest?
* Does revenue growth translate into profit growth?

## Product Intelligence

* Which products generate the most revenue?
* Which products produce the highest profit?
* Which products are destroying profitability?
* Do a small number of products drive most business revenue?

## Revenue Distribution

* How concentrated is revenue across regions and segments?
* Which segments drive the majority of revenue?
* Is the business dependent on specific segments?

---

# Project Architecture

```
Raw Transaction Data
        │
        ▼
Module 1: Data Cleaning
        │
        ▼
Cleaned Analytical Dataset
        │
        ▼
Module 2: Sales & Profit Analysis
        │
        ├── Category Performance
        ├── Regional Performance
        ├── Segment Growth Analysis
        ├── Monthly Trend Analysis
        └── Revenue Distribution
        │
        ▼
Module 3: Customer Intelligence
        │
        ├── Customer Lifetime Value
        ├── Retention Analysis
        └── RFM Segmentation
        │
        ▼
Module 4: Product Performance Intelligence
        │
        ├── Best Selling Products
        ├── Most Profitable Products
        ├── Product Profit Margin Analysis
        ├── Negative Margin Detection
        └── Pareto Product Analysis
        │
        ▼
Module 5: Advanced Insight Layer
        │
        ├── Multi-Dimensional Ranking
        ├── Profitability Efficiency Analysis
        ├── Revenue Concentration Evaluation
        └── Comparative Benchmarking
        │
        ▼
Future Dashboard Layer
```

---

# Project Structure

1. Data Preparation
2. Revenue and Profit Aggregation
3. Segment and Time-Based Growth Analysis
4. Business Insight Extraction
5. Monthly Trend Analysis
6. Revenue Contribution and Distribution Analysis
7. Customer Intelligence & Behavioral Analytics
8. Product Performance Intelligence
9. Advanced Insight Layer
10. Dashboard Layer (Future)

---

# Module 1: Data Cleaning (`module1_data_cleaning`)

Tasks performed:

* Standardized raw transactional data
* Resolved missing and inconsistent values
* Structured dataset for downstream analysis
* Validated revenue and profit fields

**Result:** Clean and analysis-ready dataset.

---

# Module 2: Sales, Profit and Growth Analysis (`module2_sales_aggregate`)

This module develops core business performance intelligence.

## Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution Percentage
* Revenue and Profit Ranking
* Detection of High-Sales / Low-Margin Categories
* Loss-Making Sub-Category Identification

## Regional Performance Analysis

* Total Sales and Profit by Region
* Profit Margin by Region
* Highest and Lowest Performing Regions
* Sales vs Profit Divergence Detection
* Regional Risk and Opportunity Classification

## Segment-Level Performance and Growth Analysis

* Total Sales by Segment
* Total Profit by Segment
* Profit Margin by Segment
* Revenue Contribution Percentage
* Average Order Value by Segment
* Segment Ranking by Revenue
* Segment Ranking by Profitability
* Annual Sales by Segment
* Annual Profit by Segment
* Year-over-Year Sales Growth
* Year-over-Year Profit Growth
* Multi-Year Growth Comparison
* Compound Annual Growth Rate per Segment

## Monthly Sales Summary

* Monthly Sales Aggregation
* Monthly Profit Aggregation
* Month-over-Month Growth
* Rolling Trend Evaluation
* Monthly Segment Performance
* Revenue Momentum Tracking

## Revenue Contribution and Distribution Analysis

* Revenue Contribution Percentage by Month
* Revenue Contribution by Segment
* Revenue Contribution by Region
* Cross-Dimensional Share Analysis
* Revenue Distribution Benchmarking
* Structural Dependency Assessment

---

# Module 3: Customer Intelligence (`module3_customer_intelligence`)

Focus: understanding **customer purchasing behavior and long-term value**.

## Customer Lifetime Value (CLV) Analysis

Metrics calculated:

* Total Revenue per Customer
* Total Profit per Customer
* Total Orders per Customer
* Average Order Value
* Estimated Customer Lifetime Value

## Customer Retention & Repeat Purchase Analysis

* Total Orders per Customer
* Repeat Purchase Detection
* Unique vs Returning Customer Analysis
* Purchase Frequency
* Retention Behavior Patterns

## RFM Customer Segmentation

Metrics used:

* **Recency:** Days since last purchase
* **Frequency:** Number of orders
* **Monetary:** Total revenue generated

Customer groups identified:

* High Value Customers
* Loyal Customers
* Potential Loyalists
* At Risk Customers
* Dormant Customers

---

# Module 4: Product Performance Intelligence (`module4_product_performance`)

Evaluates **product-level business impact and profitability efficiency.**

## Analyses Included

* Best Selling Products
* Most Profitable Products
* Low Performing Products
* Negative Margin Products
* Category Revenue Contribution
* Category Profit Contribution
* Product Profit Margin Analysis
* Pareto Product Analysis (80/20 Rule)

---

# Module 5: Advanced Analytical Insights (`module5_advanced_insights`)

This module introduces deeper analytical benchmarking techniques.

## Key Analyses

* Multi-Dimensional Ranking Models
* Profitability Efficiency Benchmarking
* Revenue vs Margin Divergence Detection
* Revenue Concentration Analysis
* Comparative Business Performance Modeling

Purpose:

Develop **decision-support intelligence beyond simple aggregation**, replicating real-world analytical evaluation used in BI teams.

---

# Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings
* Growth Rates (YoY & MoM)
* Average Order Value
* Monthly Trend Indicators
* Revenue Distribution Metrics
* Customer Lifetime Value
* Customer Retention Metrics
* Customer Behavioral Segmentation
* Product Profit Margin
* Pareto Revenue Contribution

---

# Analytical Techniques Used

* SQL Aggregations (`GROUP BY`)
* Common Table Expressions (CTE)
* Window Functions (`DENSE_RANK`, `LAG`)
* Time-Based Analysis
* Growth Rate Calculations
* Revenue Contribution Models
* Conditional Logic (`CASE`)
* Comparative Benchmarking
* Rolling Trend Evaluation
* Behavioral Segmentation Models
* Cumulative Distribution Analysis (Pareto)

---

# Business Insights Developed

* Revenue concentration differs significantly across product categories.
* High revenue categories do not always produce high margins.
* Some sub-categories operate at structural losses.
* Regional revenue scale does not always correspond to profitability.
* Segment growth rates vary significantly.
* Revenue growth does not always produce proportional profit growth.
* Customer revenue contribution is concentrated among a smaller group of buyers.
* A small percentage of products generate the majority of total revenue.
* Certain products generate revenue but destroy profitability.

---

# Tools Used

* SQL (SQLite)
* Git
* GitHub

---

# Next Evolution: **QueryForge**

The next stage of this project is an upgraded analytics system called **QueryForge**.

QueryForge will transform the current SQL-based BI project into a **full analytical query engine and interactive dashboard platform**.

## Planned Technology Stack

* **DuckDB** — Analytical database engine
* **Python** — Core language with class-based architecture
* **Pandas** — Data manipulation and transformation
* **Streamlit** — Interactive analytics dashboard

## Goal of QueryForge

Build a system that allows:

* Interactive query-driven analytics
* Dynamic insight generation
* Automated metric computation
* Real-time business dashboards

This upgrade converts the project from a **static SQL analysis repository** into a **complete analytics application.**

---

# Getting Started

Clone the repository:

```
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

Run modules in order:

```
module1_data_cleaning
module2_sales_aggregate
module3_customer_intelligence
module4_product_performance
module5_advanced_insights
```

---

# Project Status

✅ Module 1 — Data Cleaning — Completed

✅ Module 2 — Sales and Profit Analysis — Completed

✅ Module 3 — Customer Intelligence — Completed

✅ Module 4 — Product Performance Intelligence — Completed

✅ Module 5 — Advanced Analytical Insights — Completed

🚀 Next Project: **QueryForge — Analytical Query Engine + Dashboard System**
