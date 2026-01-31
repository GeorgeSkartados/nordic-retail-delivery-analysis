# Nordic Retail Delivery Analysis

This project analyzes delivery performance and revenue patterns for a Nordic retail business operating in Denmark (Copenhagen, Aarhus, Odense).

The goal is to understand how reliably orders are delivered on time, how performance changes over time, and how regions compare in terms of revenue and delivery quality.

---

## Business Questions

- Are orders delivered on time overall?
- Do delivery delays increase during specific months?
- How does delivery reliability differ by region?
- Which regions generate more revenue relative to delivery performance?

---

## What This Project Includes

### 1. Data Generation & Validation (Python + SQL)
- Simulated realistic retail order data
- Introduced seasonal delivery delays
- Calculated on-time delivery logic
- Aggregated metrics by month and region
- Exported clean CSVs for visualization

### 2. Data Visualization (Power BI)
- KPI cards for:
  - Total Revenue
  - Total Orders
  - On-Time Rate
  - Gross Margin %
- Monthly revenue and delivery trends
- Revenue by region
- Delivery performance by category
- Interactive slicers (month, region, category)

---

## Tech Stack

- Python (Pandas, SQLite)
- SQL
- Power BI
- GitHub

---

## Files

notebook/
Nordic_Retail_Delivery_Analysis.ipynb

data/
on_time_by_month.csv
on_time_by_region.csv
revenue_delivery_by_region.csv

dashboard/
Retail_KPI_Performance_Dashboard.pbix

---

## Notes

- The notebook focuses on data creation and validation.
- All insights are explored visually in Power BI.
- This project is designed to reflect real-world retail and logistics challenges in the Nordics.
