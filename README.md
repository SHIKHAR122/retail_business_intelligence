
# 📊 Retail Business Intelligence (Retail BI)

## Project Overview

This project is a structured **Retail Business Intelligence system** built using SQL to transform raw transactional data into layered business insights.

The objective is to simulate real-world BI development by progressing from:

Data Cleaning → Revenue & Profit Aggregation → Segment-Level Growth Analysis → Performance Benchmarking

All analysis is modular, documented, and designed to reflect practical BI workflows.

---

## Project Structure

1️⃣ Data Preparation
2️⃣ Revenue & Profit Aggregation
3️⃣ Segment & Time-Based Growth Analysis
4️⃣ Business Insight Extraction
5️⃣ (Upcoming) Dashboard Layer

---

## ✅ Module 1: Data Cleaning (`module1_data_cleaning`)

* Standardized raw transactional data
* Resolved missing and inconsistent values
* Structured dataset for downstream analysis
* Validated revenue and profit fields

Result: Clean, analysis-ready dataset.

---

## ✅ Module 2: Sales, Profit & Growth Analysis (`module2_sales_aggregate`)

This module expands beyond simple aggregation into profitability benchmarking and time-based growth evaluation.

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

### 🔹 Segment-Level Growth Analysis

Time-based performance evaluation using Order Date.

* Annual Sales by Segment
* Annual Profit by Segment
* Year-over-Year (YoY) Sales Growth %
* Year-over-Year Profit Growth %
* Overall Multi-Year Growth (Start vs End Comparison)
* Compound Annual Growth Rate (CAGR) per Segment

---

### 🔹 Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings
* Growth Rates (YoY & CAGR)

---

## Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions (CTEs)
* Window Functions (DENSE_RANK, LAG)
* Time-Based Functions (Year Extraction)
* Ratio & Contribution Calculations
* Growth Rate Computations (YoY, CAGR)
* Conditional Logic (CASE)
* Comparative Benchmarking

---

## Business Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue categories do not always yield high margins.
* Certain sub-categories operate at structural losses.
* Regional profitability differs from revenue scale.
* Segment growth rates differ despite similar revenue sizes.
* Revenue growth does not always translate into proportional profit growth.

---

## Upcoming Development Phase

* Monthly Trend & Momentum Analysis
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

Module 1 & Module 2 Completed
Currently expanding analytical depth and time-series evaluation.

---

