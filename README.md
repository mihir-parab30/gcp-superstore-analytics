GCP Superstore Analytics

Built an end-to-end retail analytics pipeline on Google Cloud: data in GCS → BigQuery SQL → Looker Studio insights.
Tech used: GCS, BigQuery, SQL, Looker Studio.

Steps
Step 1 – Storage (GCS)

Uploaded Superstore Orders dataset to a Google Cloud Storage bucket.

Step 2 – Warehouse (BigQuery)

Loaded the CSV from GCS into BigQuery (orders_raw) and created a cleaned table (orders_clean) with proper date fields + cleaned columns.

Step 3 – SQL Analytics (BigQuery)

Executed intermediate analytical queries:

Total Sales by Region

Average Profit by Category

Top 10 Most Profitable Products

Step 4 – Visualization (Looker Studio)

Built charts + KPI scorecards based on orders_clean:

Total Sales

Total Profit

Total Orders

Avg Discount

Bar chart: Sales by Region

Bar chart: Avg Profit by Category

Horizontal Bar: Top 10 Profitable Products

Repo Structure
gcp-superstore-analytics/
│
├─ README.md
├─ queries/
│   ├─ total_sales_by_region.sql
│   ├─ avg_profit_by_category.sql
│   └─ top10_products_profit.sql
└─ screenshots/
    ├─ kpis.png
    ├─ sales_by_region_chart.png
    ├─ avg_profit_by_category_chart.png
    └─ top10_products_chart.png

Result

Simple project showing how to go from raw CSV → cloud data warehouse → SQL → visual business insights.
