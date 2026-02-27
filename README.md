
---

# Superstore Project (Retail Business Intelligence)

## Project Overview

This project is a **Retail Business Intelligence system** that processes, cleans, and analyzes retail sales data using structured SQL workflows.

The objective is to simulate real-world BI development by transforming raw transactional data into business-level performance insights through modular design and clear documentation.

---

## Current Progress

### ✅ Module Completed: `module1_data_cleaning`

* Cleaned and standardized raw transactional data
* Handled missing values and formatting inconsistencies
* Structured dataset for analytical processing

---

### ✅ Module Completed: `module2_sales_aggregate`

This module focuses on revenue distribution, profitability evaluation, and performance benchmarking.

#### Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution Percentage
* Ranking by Revenue and Profit
* Detection of High-Sales but Low-Margin Categories
* Loss-Making Sub-Category Identification

#### Regional Analysis

* Total Sales and Profit by Region
* Profit Margin by Region
* Identification of Highest and Lowest Performing Regions
* Sales vs Profit Mismatch Detection
* Regional Performance Classification (Risk / Opportunity Zones)

#### Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings

---

## Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions (CTEs)
* Window Functions (DENSE_RANK)
* Conditional Logic (CASE)
* Ratio & Contribution Calculations
* Comparative Benchmarking (Average vs Aggregated Metrics)

---

## Business Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue segments are not always high-margin segments.
* Certain sub-categories operate at structural losses.
* Regional performance differs in both volume and profitability.
* Revenue-only evaluation can lead to misleading conclusions.

---

## Next Development Phase

* Sales Aggregation by Segment
* Monthly Sales Trend Analysis
* Time-Based Profitability Trends
* Cross-Dimensional Analysis (Region × Category × Segment)
* Dashboard & Visualization Layer

---

**Created By:** SHIKHAR SHARMA
**Project Status:** Module 1 & Module 2 Completed | Expanding Analytical Layers

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

2. Navigate to the modules folder and execute SQL scripts sequentially:

   * `module1_data_cleaning`
   * `module2_sales_aggregate`

3. Review documentation files for methodology, logic explanations, and output structure.

---
