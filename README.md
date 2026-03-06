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

All analysis is modular, documented, and designed to reflect practical BI workflows.

---

## Project Structure

1. Data Preparation
2. Revenue and Profit Aggregation
3. Segment and Time-Based Growth Analysis
4. Business Insight Extraction
5. Monthly Trend Analysis (Completed)
6. Revenue Contribution and Distribution Analysis (Completed)
7. Ranking and Advanced Insight Analysis (In Progress)
8. Dashboard Layer (Upcoming)

---

## Module 1: Data Cleaning (`module1_data_cleaning`)

* Standardized raw transactional data
* Resolved missing and inconsistent values
* Structured dataset for downstream analysis
* Validated revenue and profit fields

Result: Clean, analysis-ready dataset.

---

## Module 2: Sales, Profit and Growth Analysis (`module2_sales_aggregate`)

This module expands beyond simple aggregation into profitability benchmarking, structural distribution analysis, and advanced performance intelligence.

---

### Category-Level Analysis

* Total Sales by Category
* Total Profit by Category
* Profit Margin Calculation
* Revenue Contribution Percentage
* Revenue and Profit Ranking
* Detection of High-Sales / Low-Margin Categories
* Loss-Making Sub-Category Identification

---

### Regional Performance Analysis

* Total Sales and Profit by Region
* Profit Margin by Region
* Highest and Lowest Performing Regions
* Sales vs Profit Divergence Detection
* Regional Risk and Opportunity Classification

---

### Segment-Level Performance and Growth Analysis (Completed)

Time-based and structural evaluation using Order Date.

* Total Sales by Segment
* Total Profit by Segment
* Profit Margin by Segment
* Revenue Contribution Percentage by Segment
* Average Order Value by Segment
* Segment Ranking by Revenue
* Segment Ranking by Profitability
* Annual Sales by Segment
* Annual Profit by Segment
* Year-over-Year Sales Growth Percentage
* Year-over-Year Profit Growth Percentage
* Overall Multi-Year Growth Comparison
* Compound Annual Growth Rate per Segment

This phase establishes customer-segmentation intelligence and profitability benchmarking.

---

### Monthly Sales Summary (Completed)

Time-series intelligence developed at a monthly level.

* Monthly Sales Aggregation
* Monthly Profit Aggregation
* Month-over-Month Growth Percentage
* Rolling Trend Evaluation
* Monthly Performance Trends by Segment
* Revenue Momentum Tracking

This phase transitions the system from static analysis to dynamic trend monitoring.

---

### Revenue Contribution and Distribution Analysis (Completed)

Structural revenue modeling implemented across business dimensions.

* Revenue Contribution Percentage by Month
* Revenue Contribution Percentage by Segment
* Revenue Contribution Percentage by Region
* Cross-Dimensional Share Analysis (Segment and Month)
* Revenue Distribution Benchmarking
* Structural Dependency Assessment

This phase establishes proportional revenue intelligence and distribution benchmarking.

---

### Ranking and Advanced Insight Analysis (In Progress)

Currently building a deeper comparative intelligence layer focused on:

* Multi-Dimensional Ranking (Segment by Region by Category)
* Profitability Efficiency Ranking
* Revenue vs Margin Divergence Analysis
* Concentration Risk Evaluation
* Advanced Comparative Benchmarking Models

This phase elevates the system from descriptive analytics to structured performance scoring and insight prioritization.

---

## Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings
* Growth Rates (Year-over-Year, Compound Annual, Month-over-Month)
* Average Order Value
* Monthly Trend Indicators
* Revenue Distribution Metrics

---

## Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions
* Window Functions (DENSE_RANK, LAG)
* Time-Based Functions (Year and Month Extraction)
* Ratio and Contribution Calculations
* Growth Rate Computations
* Conditional Logic (CASE)
* Comparative Benchmarking
* Rolling Trend Evaluation
* Multi-Dimensional Ranking Models

---

## Business Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue categories do not always yield high margins.
* Certain sub-categories operate at structural losses.
* Regional profitability differs from revenue scale.
* Segment growth rates differ despite similar revenue sizes.
* Revenue growth does not always translate into proportional profit growth.
* Monthly analysis reveals measurable volatility and momentum shifts.
* Revenue distribution analysis exposes structural dependency patterns.

---

## Upcoming Development Phase

* Complete Advanced Ranking Models
* Margin Trend Over Time
* Cross-Dimensional Analysis (Region by Segment by Category)
* Executive KPI Dashboard Layer

---

## Tools Used

* SQL (SQLite)
* Git
* GitHub

---

## Getting Started

Clone the repository:

```
git clone https://github.com/SHIKHAR122/retail_business_intelligence.git
```

Execute in order:

* module1_data_cleaning
* module2_sales_aggregate

---

## Project Status

Module 1 Completed
Module 2 Sales, Profit and Segment Analysis Completed
Monthly Sales Summary Completed
Revenue Contribution and Distribution Analysis Completed
Ranking and Advanced Insight Analysis In Progress

Currently building advanced comparative intelligence and preparing the analytical system for executive-level dashboard integration.

---
