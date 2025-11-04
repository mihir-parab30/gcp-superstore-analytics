# GCP Superstore Analytics

This MLOps Lab shows a clean retail analytics workflow on Google Cloud:  
CSV → GCS Bucket → BigQuery SQL → Looker Studio dashboards.

Tech used: **GCS, BigQuery, SQL, Looker Studio**

---

## Architecture

| Step | Tool | Action |
|------|------|--------|
| 1 | GCS | Uploaded Superstore Orders CSV file |
| 2 | BigQuery | Loaded raw → cleaned table + ran aggregations |
| 3 | Looker Studio | Built business insights dashboards |

---

## Key Insights Generated

- Total Sales by Region
- Average Profit by Category
- Top 10 Most Profitable Products
- KPI boxes → Total Sales / Total Profit / Total Orders

---

## SQL Queries

queries stored inside `/sql_queries/`

---

## Screenshots

### GCS Bucket – Raw CSV Uploaded
![GCS Bucket](./assets/gcs_bucket.png)

### BigQuery – Tables Created
![BigQuery Tables](./assets/bigquery_tables.png)

### Sales by Region
![Sales Region](./assets/total_sales_by_region.png)

### Final Looker Studio Visualization
![Looker Viz](./assets/looker_studio_viz.png)

---

## Result

This project shows end-to-end analytical skills using Google Cloud — from ingestion → warehouse → business dashboards.
