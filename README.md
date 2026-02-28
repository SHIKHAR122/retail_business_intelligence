# 📊 Retail Business Intelligence (Retail BI)

## Project Overview

This project is a **Retail Business Intelligence system** built using structured SQL workflows to transform raw transactional retail data into multi-layered business insights.

The objective is to simulate real-world BI development by progressing from data cleaning → aggregation → profitability analysis → growth evaluation → performance comparison — using modular design and documented logic.

---

## Project Architecture

The system is designed in analytical layers:

1. Data Cleaning & Structuring
2. Revenue & Profit Aggregation
3. Segment-Level Growth Analysis
4. Multi-Dimensional Performance Comparison
5. Business Insight Extraction
6. (Upcoming) Dashboard & Visualization Layer

---

## ✅ Module 1: Data Cleaning (`module1_data_cleaning`)

* Standardized raw transactional records
* Handled missing values and formatting inconsistencies
* Structured dataset for downstream analytical processing
* Validated numerical fields for revenue and profitability accuracy

Result: Clean, analysis-ready dataset.

---

## ✅ Module 2: Sales & Profit Aggregation (`module2_sales_aggregate`)

### Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution %
* Ranking by Revenue & Profit
* Detection of High-Sales / Low-Margin Categories
* Identification of Loss-Making Sub-Categories

### Regional Analysis

* Total Sales & Profit by Region
* Profit Margin by Region
* Highest vs Lowest Performing Regions
* Sales vs Profit Mismatch Detection
* Regional Risk / Opportunity Classification

### Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings

---

## ✅ Module 3: Segment Growth & Time-Based Analysis (`module3_segment_growth_analysis`)

This module introduces time-series evaluation and growth benchmarking.

### Annual Segment Performance

* Annual Sales by Segment
* Annual Profit by Segment
* Revenue Trend Comparison Across Years

### Growth Metrics Calculated

* Year-over-Year (YoY) Sales Growth %
* Year-over-Year Profit Growth %
* Overall Multi-Year Growth (Start vs End)
* Compound Annual Growth Rate (CAGR) per Segment

### Analytical Focus

* Growth Rate Comparison (Momentum vs Size)
* Stability vs Volatility Evaluation
* Sales Growth vs Profit Growth Divergence
* Identification of Structurally Accelerating Segments

Key Insight:
Revenue growth does not automatically imply profitability growth. Segment-level margin expansion is critical for sustainable performance.

---

## Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions (CTEs)
* Window Functions (DENSE_RANK, LAG)
* Time-Based Functions (Year Extraction)
* Ratio & Contribution Calculations
* Growth Rate Formulas (YoY, CAGR)
* Conditional Classification (CASE Logic)
* Comparative Performance Benchmarking

---

## Business-Level Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue segments are not always high-margin segments.
* Certain sub-categories operate at structural losses.
* Regional profitability differs from regional sales volume.
* Segment growth rates differ despite similar revenue sizes.
* Some segments show revenue growth without proportional profit expansion.

---

## Upcoming Development Phase

* Monthly Growth & Trend Acceleration Analysis
* Profit Margin Trend Over Time
* Cross-Dimensional Evaluation (Region × Segment × Category)
* Executive-Level KPI Dashboard Layer
* Visualization Integration

---

## Tools Used

* SQL (SQLite Environment)
* Git for Version Control
* GitHub for Repository Management

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

2. Execute SQL modules sequentially:

* `module1_data_cleaning`
* `module2_sales_aggregate`
* `module3_segment_growth_analysis`

3. Review documented queries for methodology and analytical reasoning.

---

## Project Status

Modules 1–3 Completed
Currently expanding time-series and strategic growth analysis layers.

---
