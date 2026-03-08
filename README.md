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
* Ranking and Advanced Insight Analysis
* Customer Behavioral Intelligence

All analysis is modular, documented, and designed to reflect practical BI workflows.

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
Advanced Insight Layer
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
5. Monthly Trend Analysis (Completed)
6. Revenue Contribution and Distribution Analysis (Completed)
7. Ranking and Advanced Insight Analysis (In Progress)
8. Customer Intelligence & Behavioral Analytics (Completed)
9. Product Performance Analysis (Upcoming)
10. Dashboard Layer (Upcoming)

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

---

## Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution Percentage
* Revenue and Profit Ranking
* Detection of High-Sales / Low-Margin Categories
* Loss-Making Sub-Category Identification

---

## Regional Performance Analysis

* Total Sales and Profit by Region
* Profit Margin by Region
* Highest and Lowest Performing Regions
* Sales vs Profit Divergence Detection
* Regional Risk and Opportunity Classification

---

## Segment-Level Performance and Growth Analysis (Completed)

Time-based evaluation using order date.

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

---

## Monthly Sales Summary (Completed)

Time-series business intelligence.

* Monthly Sales Aggregation
* Monthly Profit Aggregation
* Month-over-Month Growth
* Rolling Trend Evaluation
* Monthly Segment Performance
* Revenue Momentum Tracking

---

## Revenue Contribution and Distribution Analysis (Completed)

Structural revenue distribution modeling.

* Revenue Contribution Percentage by Month
* Revenue Contribution by Segment
* Revenue Contribution by Region
* Cross-Dimensional Share Analysis
* Revenue Distribution Benchmarking
* Structural Dependency Assessment

---

## Ranking and Advanced Insight Analysis (In Progress)

Building deeper comparative intelligence:

* Multi-Dimensional Ranking (Segment × Region × Category)
* Profitability Efficiency Ranking
* Revenue vs Margin Divergence Analysis
* Concentration Risk Evaluation
* Comparative Benchmarking Models

---

# Module 3: Customer Intelligence (`module3_customer_intelligence`)

Focus: understanding **customer purchasing behavior and long-term value**.

---

## Customer Lifetime Value (CLV) Analysis (Completed)

Metrics calculated:

* Total Revenue per Customer
* Total Profit per Customer
* Total Orders per Customer
* Average Order Value
* Estimated Customer Lifetime Value

Purpose: identify **high-value customers** and revenue concentration.

---

## Customer Retention & Repeat Purchase Analysis (Completed)

* Total Orders per Customer
* Repeat Purchase Detection
* Unique vs Returning Customer Analysis
* Purchase Frequency
* Retention Behavior Patterns

Purpose: measure **customer loyalty and engagement**.

---

## RFM Customer Segmentation (Completed)

Customer segmentation using the **Recency–Frequency–Monetary model**.

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

Purpose: build **behavior-based customer intelligence**.

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

---

# Business Insights Developed

* Revenue concentration differs significantly across product categories.
* High revenue categories do not always produce high margins.
* Some sub-categories operate at structural losses.
* Regional revenue scale does not always correspond to profitability.
* Segment growth rates vary significantly.
* Revenue growth does not always produce proportional profit growth.
* Monthly trend analysis reveals volatility and momentum shifts.
* Revenue distribution analysis exposes dependency patterns.
* Customer revenue contribution is concentrated among a smaller group of buyers.
* Repeat purchase behavior strongly influences overall revenue generation.

---

# Upcoming Development Phase

Next development layer will include:

* Advanced Ranking Models
* Margin Trend Over Time
* Cross-Dimensional Analysis
* Product Performance Analysis
* Executive Dashboard Layer

---

# Tools Used

* SQL (SQLite)
* Git
* GitHub

---

# Getting Started

Clone the repository:

```
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

Run modules in order:

1. module1_data_cleaning
2. module2_sales_aggregate
3. module3_customer_intelligence

---

# Project Status

* Module 1 — Data Cleaning — Completed

* Module 2 — Sales and Profit Analysis — Completed

* Monthly Sales Summary — Completed

* Revenue Contribution Analysis — Completed

* Ranking & Advanced Insights — In Progress

* Module 3 — Customer Intelligence — Completed

* Customer Lifetime Value Analysis — Completed

* Customer Retention Analysis — Completed

* RFM Customer Segmentation — Completed

Next Phase: **Product Performance Analysis**
