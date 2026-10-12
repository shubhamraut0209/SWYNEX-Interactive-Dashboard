# SWYNEX Task 3 — Interactive E-commerce Dashboard

## Overview
A self-contained interactive dashboard created for Task 3 of the SWYNEX Technologies Data Analyst Internship. It uses the cleaned e-commerce retail transaction dataset from Task 1 and the analysis completed in Task 2.

## Open the dashboard
Open `SWYNEX_Ecommerce_Interactive_Dashboard.html` in a modern browser (Chrome, Edge, or Firefox). The dashboard includes embedded Plotly JavaScript and embedded data, so no installation or server is required.

## KPIs
- Estimated net sales
- Estimated gross sales
- Transaction records
- Average customer rating (available ratings only)

## Visualizations
- Estimated net sales by product category
- Monthly estimated net sales
- Transaction count by payment method
- Order-status distribution
- Estimated net sales by country
- Customer-rating distribution

## Interactive filters
- Start and end date
- Product category
- Country
- Payment method

All KPIs, charts, and insight cards update when filters change. Use **Reset filters** to return to the full dataset.

## Data and calculation notes
- Dataset: 11,814 rows and 13 original columns.
- Estimated gross sales = quantity × unit price.
- Estimated discount = gross sales × discount percentage ÷ 100.
- Estimated net sales = gross sales − estimated discount.
- These estimates do not independently account for tax, shipping, refunds, returns, or other adjustments unless already reflected in the dataset.
- Transaction records are treated as rows; validate business definitions before interpreting them as unique orders or accounting revenue.
- Customer rating averages exclude missing ratings.

## Files
- `SWYNEX_Ecommerce_Interactive_Dashboard.html` — complete interactive dashboard
- `ecommerce_retail_transactions_cleaned.csv` — dataset used by the dashboard

## Skills demonstrated
Exploratory data analysis, KPI design, data visualization, sales metrics, filter-driven dashboarding, data-quality interpretation, and business communication.

**Author:** Shubham Umesh Raut  
**Project:** SWYNEX Technologies — Data Analyst Internship, Task 3
