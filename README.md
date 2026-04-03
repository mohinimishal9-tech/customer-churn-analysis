# Customer Churn Analysis

## Project Overview
This project analyzes customer churn behavior for a 
bank with 10,000 customers across France, Germany, 
and Spain. The goal is to identify key churn drivers 
and high-risk customer segments using SQL and 
visualized in Power BI.

## Dataset
- 10,000 bank customer records
- Source: SQL Database (churn_db)
- Fields: CustomerID, Age, Gender, Geography, 
  CreditScore, Balance, Tenure, NumOfProducts, 
  HasCrCard, IsActiveMember, EstimatedSalary, Exited

## SQL Analysis
- Extracted and transformed raw customer data using SQL
- Calculated churn rate, active customers, and 
  retention rate through SQL queries
- Segmented customers by geography, age group, 
  product usage, and credit card ownership
- Identified high-risk customer profiles using 
  conditional logic and aggregations

## Power BI Dashboard
Three-page interactive dashboard built on SQL data:
- **Page 1 — Overview:** Total customers, churn rate, 
  retention rate and geographic churn distribution
- **Page 2 — Segmentation:** Churn breakdown by age 
  group, tenure, products and credit card ownership
- **Page 3 — Financial & Risk Profile:** Average balance 
  and credit score comparison between churned and 
  retained customers, churn rate by geography and 
  age group

## Key Findings
- Overall churn rate: 20.4%
- Germany has the highest churn rate at 32%
- Customers aged 50-59 have the highest churn rate at 56%
- Churned customers hold higher average balances — 
  the bank is losing its most valuable clients
- Customers with 4 products churn at near 100% rate

## Tools & Technologies
- SQL (data extraction and transformation)
- Power BI Desktop (visualization)
- DAX (calculated measures and columns)

## Author
Your Name
LinkedIn: [your LinkedIn URL]
