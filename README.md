# 📊 Retail Business Intelligence (Retail BI)

## Project Overview

This project is a structured **Retail Business Intelligence system** built using SQL to transform raw transactional data into layered business insights.

The objective is to simulate real-world BI development by progressing from:

Data Cleaning → Revenue & Profit Aggregation → Segment-Level Growth Analysis → Performance Benchmarking → Time-Series & Seasonality Evaluation

All analysis is modular, documented, and designed to reflect practical BI workflows.

---

## Project Structure

1️⃣ Data Preparation
2️⃣ Revenue & Profit Aggregation
3️⃣ Segment & Time-Based Growth Analysis
4️⃣ Business Insight Extraction
5️⃣ Monthly & Seasonality Analysis (In Progress)
6️⃣ (Upcoming) Dashboard Layer

---

## ✅ Module 1: Data Cleaning (`module1_data_cleaning`)

* Standardized raw transactional data
* Resolved missing and inconsistent values
* Structured dataset for downstream analysis
* Validated revenue and profit fields

Result: Clean, analysis-ready dataset.

---

## ✅ Module 2: Sales, Profit & Growth Analysis (`module2_sales_aggregate`)

This module expands beyond simple aggregation into profitability benchmarking, segment intelligence, and time-based performance evaluation.

---

### 🔹 Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution %
* Revenue & Profit Ranking
* Detection of High-Sales / Low-Margin Categories
* Loss-Making Sub-Category Identification

---

### 🔹 Regional Performance Analysis

* Total Sales & Profit by Region
* Profit Margin by Region
* Highest vs Lowest Performing Regions
* Sales vs Profit Divergence Detection
* Regional Risk / Opportunity Classification

---

### 🔹 Segment-Level Performance & Growth Analysis (Completed)

Time-based and structural evaluation using Order Date.

* Total Sales by Segment
* Total Profit by Segment
* Profit Margin by Segment
* Revenue Contribution % by Segment
* Average Order Value (AOV) by Segment
* Segment Ranking by Revenue
* Segment Ranking by Profitability
* Annual Sales by Segment
* Annual Profit by Segment
* Year-over-Year (YoY) Sales Growth %
* Year-over-Year Profit Growth %
* Overall Multi-Year Growth (Start vs End Comparison)
* Compound Annual Growth Rate (CAGR) per Segment

This phase establishes customer-segmentation intelligence and profitability benchmarking.

---

### 🔹 Monthly Sales Summary & Seasonality Analysis (In Progress)

Currently expanding time-series intelligence at a monthly level with focus on seasonality detection:

* Monthly Sales Aggregation
* Monthly Profit Aggregation
* Month-over-Month (MoM) Growth %
* Rolling Trend Evaluation
* Seasonal Pattern Detection (Peak vs Off-Peak Months)
* Monthly Performance Trends by Segment

This phase introduces momentum tracking and seasonality modeling, strengthening forecasting and executive reporting readiness.

---

### 🔹 Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings
* Growth Rates (YoY, CAGR, MoM)
* Average Order Value (AOV)

---

## Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions (CTEs)
* Window Functions (DENSE_RANK, LAG)
* Time-Based Functions (Year & Month Extraction)
* Ratio & Contribution Calculations
* Growth Rate Computations (YoY, CAGR, MoM)
* Conditional Logic (CASE)
* Comparative Benchmarking
* Trend & Seasonality Evaluation Techniques

---

## Business Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue categories do not always yield high margins.
* Certain sub-categories operate at structural losses.
* Regional profitability differs from revenue scale.
* Segment growth rates differ despite similar revenue sizes.
* Revenue growth does not always translate into proportional profit growth.
* Emerging seasonal patterns indicate uneven revenue distribution across months.

---

## Upcoming Development Phase

* Complete Seasonality Benchmarking Across Segments
* Margin Trend Over Time
* Cross-Dimensional Analysis (Region × Segment × Category)
* Executive KPI Dashboard Layer

---

## Tools Used

* SQL (SQLite)
* Git (Version Control)
* GitHub (Repository Management)

---

## Getting Started

```bash
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

Execute in order:

* `module1_data_cleaning`
* `module2_sales_aggregate`

---

## Project Status

Module 1 Completed
Module 2 – Sales, Profit & Segment Analysis Completed
Monthly Sales Summary & Seasonality Trend Analysis – In Progress

Currently deepening time-series intelligence and preparing for dashboard integration.

---
