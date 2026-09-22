# Nike Sales Analytics & Power BI Dashboard

## Project Overview
This portfolio project demonstrates an end-to-end Data Analysis and Business Intelligence pipeline. The goal is to ingest, clean, and transform uncleaned Nike retail sales data using **Python (Pandas)**, and build an interactive **Power BI Dashboard** tailored for Small and Medium Businesses (SMBs) to track revenue, profit margins, and regional performance.

## Key Features & Business Logic (ETL)
- **Data Cleaning & Standardization:** Standardized product sizes (`Size`), cleaned numeric outliers in units sold and prices, and normalized region names (fixing typos like `bengaluru` and `Hyd`).
- **Financial Audit & Recalculation:** Recalculated net `Revenue` based on standard e-commerce formulas (`Units * MRP * (1 - Discount)`) and estimated `Profit` using a standard 40% gross margin.
- **Data Integrity:** Handled missing values and structured a production-ready dataset (`nike_sales_clean.csv`).

## Power BI Dashboard Highlights
- **Executive KPI Summary:** Total Revenue (4.21M), Total Profit (1.68M), Total Units Sold, and Profit Margin (40%).
- **Geographic & Channel Breakdown:** City-level performance analysis alongside an Online vs. Retail sales channel comparison.
- **Interactive Slicers:** Dynamic filtering by demographic categories (`Gender`).

## Files in this Repository
- `nike_sales_etl.py`: Python script containing the full ETL pipeline.
- `nike_sales_clean.csv`: Cleaned dataset ready for consumption.
- `nike_sales_dashboard.pbix`: Power BI file.
- `dashboard_preview.png`: Visual preview of the dashboard.
