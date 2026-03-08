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

# Project Structure

1. Data Preparation
2. Revenue and Profit Aggregation
3. Segment and Time-Based Growth Analysis
4. Business Insight Extraction
5. Monthly Trend Analysis (Completed)
6. Revenue Contribution and Distribution Analysis (Completed)
7. Ranking and Advanced Insight Analysis (In Progress)
8. Customer Intelligence & Behavioral Analytics (In Progress)
9. Dashboard Layer (Upcoming)

---

# Module 1: Data Cleaning (`module1_data_cleaning`)

* Standardized raw transactional data
* Resolved missing and inconsistent values
* Structured dataset for downstream analysis
* Validated revenue and profit fields

Result: Clean, analysis-ready dataset.

---

# Module 2: Sales, Profit and Growth Analysis (`module2_sales_aggregate`)

This module expands beyond simple aggregation into profitability benchmarking, structural distribution analysis, and advanced performance intelligence.

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

## Monthly Sales Summary (Completed)

Time-series intelligence developed at a monthly level.

* Monthly Sales Aggregation
* Monthly Profit Aggregation
* Month-over-Month Growth Percentage
* Rolling Trend Evaluation
* Monthly Performance Trends by Segment
* Revenue Momentum Tracking

This phase transitions the system from static analysis to dynamic trend monitoring.

---

## Revenue Contribution and Distribution Analysis (Completed)

Structural revenue modeling implemented across business dimensions.

* Revenue Contribution Percentage by Month
* Revenue Contribution Percentage by Segment
* Revenue Contribution Percentage by Region
* Cross-Dimensional Share Analysis (Segment and Month)
* Revenue Distribution Benchmarking
* Structural Dependency Assessment

This phase establishes proportional revenue intelligence and distribution benchmarking.

---

## Ranking and Advanced Insight Analysis (In Progress)

Currently building a deeper comparative intelligence layer focused on:

* Multi-Dimensional Ranking (Segment by Region by Category)
* Profitability Efficiency Ranking
* Revenue vs Margin Divergence Analysis
* Concentration Risk Evaluation
* Advanced Comparative Benchmarking Models

This phase elevates the system from descriptive analytics to structured performance scoring and insight prioritization.

---

# Module 3: Customer Intelligence & Behavioral Analytics (`module3_customer_intelligence`)

This module focuses on analyzing customer purchasing behavior to generate insights about customer value, retention patterns, and behavioral segmentation.

---

## Customer Lifetime Value (CLV) Analysis (Completed)

* Total Revenue per Customer
* Total Profit per Customer
* Total Orders per Customer
* Average Order Value per Customer
* Estimated Customer Lifetime Value

This phase identifies high-value customers and quantifies their long-term revenue contribution.

---

## Customer Retention & Repeat Purchase Analysis (Completed)

* Total Orders per Customer
* Repeat Purchase Detection
* Unique vs Returning Customer Analysis
* Customer Purchase Frequency
* Retention Rate Evaluation

This phase establishes customer loyalty and engagement insights.

---

## RFM Customer Segmentation (In Progress)

Developing behavioral customer segmentation using the **Recency–Frequency–Monetary (RFM)** framework.

Metrics being implemented:

* Recency (Days since last purchase)
* Frequency (Total orders per customer)
* Monetary Value (Total revenue generated by customer)

The goal is to classify customers into behavioral segments such as:

* High-Value Customers
* Loyal Customers
* Potential Loyalists
* At-Risk Customers
* Dormant Customers

This phase introduces structured **customer behavioral intelligence and segmentation modeling**.

---

# Core Metrics Generated

* Total Revenue
* Total Profit
* Profit Margin
* Revenue Share
* Performance Rankings
* Growth Rates (Year-over-Year, Compound Annual, Month-over-Month)
* Average Order Value
* Monthly Trend Indicators
* Revenue Distribution Metrics
* Customer Lifetime Value
* Customer Retention Metrics

---

# Analytical Techniques Used

* GROUP BY Aggregations
* Common Table Expressions
* Window Functions (`DENSE_RANK`, `LAG`)
* Time-Based Functions (Year and Month Extraction)
* Ratio and Contribution Calculations
* Growth Rate Computations
* Conditional Logic (`CASE`)
* Comparative Benchmarking
* Rolling Trend Evaluation
* Multi-Dimensional Ranking Models
* Behavioral Customer Segmentation

---

# Business Insights Developed

* Revenue concentration varies significantly across categories.
* High-revenue categories do not always yield high margins.
* Certain sub-categories operate at structural losses.
* Regional profitability differs from revenue scale.
* Segment growth rates differ despite similar revenue sizes.
* Revenue growth does not always translate into proportional profit growth.
* Monthly analysis reveals measurable volatility and momentum shifts.
* Revenue distribution analysis exposes structural dependency patterns.
* Customer revenue contribution is concentrated among a smaller subset of customers.
* Repeat purchasing behavior strongly influences total revenue generation.

---

# Upcoming Development Phase

* Complete Advanced Ranking Models
* Margin Trend Over Time
* Cross-Dimensional Analysis (Region by Segment by Category)
* Customer Cohort Retention Analysis
* Executive KPI Dashboard Layer

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

Execute in order:

* module1_data_cleaning
* module2_sales_aggregate
* module3_customer_intelligence

---

# Project Status

Module 1 Completed
Module 2 Sales, Profit and Segment Analysis Completed
Monthly Sales Summary Completed
Revenue Contribution and Distribution Analysis Completed
Ranking and Advanced Insight Analysis In Progress

Module 3 Customer Intelligence Initiated
Customer Lifetime Value Analysis Completed
Customer Retention & Repeat Purchase Analysis Completed
RFM Customer Segmentation In Progress

Currently building advanced comparative intelligence and customer behavioral segmentation before moving toward dashboard integration.

---

If you want, I can also show you **one small addition to the README that makes your repo look like a real production analytics project (something most candidates miss).**
