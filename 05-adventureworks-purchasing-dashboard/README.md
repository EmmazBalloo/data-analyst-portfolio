# AdventureWorks Purchasing & Vendor Analytics Dashboard

**Tools:** Power BI | DAX | Supply Chain Analytics | Data Modeling

## Overview
A 5-page Power BI dashboard analyzing purchasing spend and vendor performance using the AdventureWorks Purchasing dataset.

## Dataset Scope
- $70.48M in total purchasing spend analyzed
- 104 active vendors
- 4K purchase orders
- 8 product categories

## What Was Done
- Modeled 8 tables including Purchase Order Header, Purchase Order Detail, Vendor, Ship Method, Product Vendor, and Product Category with correct star schema relationships.
- Developed 18 DAX measures, including Total Purchase Spend, Average Lead Time, Average Fulfillment Days, Rejection Rate %, and Top 5 Vendor % of Spend.

## Key Insights
- 80.72% of spend goes to Excellent-rated vendors.
- Top 5 vendors account for ~25% of total spend.
- Average lead time: 19.45 days; average fulfillment time: 9.05 days.
- The Tires & Tubes subcategory drives ~35% of subcategory purchasing spend.

## Key Files
- `adventureworks_purchasing.pbix` — full Power BI dashboard
- `visuals/` — screenshots of each dashboard page

## How to View
Open `adventureworks_purchasing.pbix` in Power BI Desktop, or refer to the screenshots in `visuals/` for a quick preview.
