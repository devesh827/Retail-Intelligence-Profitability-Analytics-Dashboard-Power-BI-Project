# Retail Intelligence & Profitability Analytics Dashboard

## Project Overview

This project is an end-to-end Business Intelligence solution built using Power BI to analyze retail sales performance, profitability, and marketing effectiveness. The dashboard provides actionable insights for business stakeholders including CEO, CFO, and CMO through interactive reports and KPI tracking.

The solution combines data from multiple sales channels, product master data, vendor cost agreements, marketing budgets, and campaign performance datasets to support data-driven decision-making.

---

## Business Objectives

* Monitor overall sales performance and growth trends
* Analyze customer orders and purchasing behavior
* Evaluate product profitability and gross margins
* Simulate vendor discount scenarios using What-if Analysis
* Measure marketing campaign effectiveness and budget efficiency
* Provide executive-level dashboards for strategic decision-making

---

## Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Modeling
* Microsoft Excel
* Business Intelligence

---

## Dataset Overview

The project integrates multiple datasets:

### Sales Data

* D2C Sales
* Nile Marketplace Sales
* DCart Sales

### Product Data

* Product Master

### Cost Data

* Vendor Cost Agreements

### Marketing Data

* Marketing Budget
* Campaign Performance Data

---

## ETL Process (Power Query)

### Data Cleaning & Transformation

* Removed unnecessary columns and rows
* Fixed data types and date formats
* Standardized column names
* Handled missing values
* Validated data quality

### Data Integration

* Appended multiple sales sources into a single Fact_Sales table
* Unpivoted Marketing Budget data
* Unpivoted Cost Agreement data
* Created clean and analysis-ready datasets

---

## Data Model

### Fact Tables

* Fact_Sales
* Fact_Cost
* Fact_Marketing_Budget
* Fact_Marketing_Campaign

### Dimension Tables

* Dim_Date
* Dim_Product
* Dim_Category

### Model Design

* Star Schema Architecture
* Optimized relationships for reporting and performance

---

## Key DAX Measures

### CEO Metrics

* Total Revenue
* Total Units Sold
* Total Orders
* Total Customers
* Average Selling Price (ASP)
* Return Rate %
* Previous Month Revenue
* Revenue Growth %
* YTD Revenue
* Average Order Value

### CFO Metrics

* Product Cost
* Monthly Volume
* Discount Eligibility
* Volume Discount Amount
* Net Vendor Payable
* Gross Profit
* Gross Margin %

### CMO Metrics

* Total Impressions
* Total Clicks
* CTR %
* Add-to-Cart Rate %
* Average CPC
* Total Marketing Budget
* Revenue per ₹ Spent

---

## Advanced Features

### Dynamic Product Cost Calculation

Implemented advanced DAX using SUMX, CALCULATE, FILTER, and VAR to identify the correct product cost based on SKU and vendor agreement validity periods.

### What-if Analysis

Created a Volume Threshold parameter allowing finance teams to simulate different vendor discount scenarios and analyze their impact on profitability.

### Time Intelligence

Implemented:

* Previous Month Revenue
* Revenue Growth %
* YTD Revenue

---

## Dashboard Pages

### CEO Dashboard

* Revenue Overview
* Sales Trends
* Category Performance
* Channel Analysis
* Return Analysis

### CFO Dashboard

* Product Cost Analysis
* Profitability Trends
* Gross Margin Analysis
* What-if Discount Simulation

### CMO Dashboard

* Campaign Performance
* CTR Analysis
* Add-to-Cart Conversion Analysis
* Marketing Budget Efficiency

---

## Key Insights

* Identified top-performing product categories and sales channels
* Evaluated profitability impact of changing vendor agreements
* Measured marketing effectiveness through CTR and conversion metrics
* Enabled dynamic financial scenario analysis using What-if Parameters

---

## Skills Demonstrated

* Power BI Dashboard Development
* Power Query ETL
* Data Modeling
* Advanced DAX
* Business Analytics
* Time Intelligence
* What-if Analysis
* Data Visualization
* Executive Reporting

---

## Project Outcome

Built a complete Business Intelligence solution that transforms raw business data into actionable insights, enabling executive stakeholders to monitor performance, optimize profitability, and improve marketing effectiveness through interactive dashboards.

---

## Dashboard Preview

(Add screenshots here)

CEO Dashboard

CFO Dashboard

CMO Dashboard

---

## Author

Devesh Kumar
