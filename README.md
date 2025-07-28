# Sales-Performance-Analysis

## Problem Statement
The company seeks to better understand its overall sales performance across three core areas:
- Revenue trends – over time and across regions
- Customer behavior – who is buying what and how much ?
- Sales team performance – are targets being met?

## Data Collection
- Source : Kaggle
- There are 4 csv files (customers - products - salesperson - sales_data)

## Data Cleaning
- Verified correct data types
- Removed duplicates in customer, product, and salesperson records
- Standardized region, gender, and age group values
- Created key calculated columns in Power BI:
  - Total_Sales = Quantity × Unit Price × (1 - Discount)
  - Total_Cost = Quantity × Cost Price (via RELATED)
  - Profit = Total_Sales - Total_Cost
 
## Exploratory Data Analysis (EDA)
- Total revenue: $ 1.93M
- Highest-spending customer group: Age 26–35
- Top-selling product category: Toys
- Most profitable region: East

## Visualizations
The analysis was split across 3 main dashboards in Power BI:
- 1. Sales Overview Dashboard
- 2. Product & Customer Insights Dashboard
- 3. Sales Team Performance Dashboard
