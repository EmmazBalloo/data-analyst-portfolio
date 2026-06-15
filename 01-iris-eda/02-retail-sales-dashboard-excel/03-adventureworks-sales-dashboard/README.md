# AdventureWorks Sales & Customer Analytics Dashboard

**Tools:** Power BI | DAX | Star Schema Modeling | Data Visualization

## Overview
A 5-page interactive Power BI dashboard analyzing sales and customer performance using the AdventureWorks Cycles dataset.

## Dataset Scope
- £123.22M in total revenue analyzed
- 31K orders
- 19K customers
- 10 global sales territories

## What Was Done
- Designed a star schema data model connecting 9 tables (Sales Order Header, Sales Order Detail, Customer, Product, Territory, and others) with correct Many-to-One relationships.
- Built a custom Date table for time intelligence.
- Developed 16 DAX measures, including Total Revenue, YoY Growth %, Repeat Customers, Average Order Value, and Top 10 Customer % of Revenue.

## Key Insights
- Bikes drive 87% of total revenue.
- 87.9% of orders are online-driven.
- Year-over-year revenue growth of 69.19%.
- The top 10 customers account for just 7.25% of total revenue — indicating a healthy, distributed customer base.

## Key Files
- `adventureworks_sales.pbix` — full Power BI dashboard
- `visuals/` — screenshots of each dashboard page

## How to View
Open `adventureworks_sales.pbix` in Power BI Desktop, or refer to the screenshots in `visuals/` for a quick preview.
