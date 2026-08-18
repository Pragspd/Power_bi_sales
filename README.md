# Power_bi_sales
Interactive Power BI dashboard analyzing Amazon product sales — YTD/QTD trends, category performance, and top SKUs by revenue and reviews.
📊 Amazon Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard analyzing Amazon product sales performance — built to track YTD/QTD sales trends, product category performance, and top-performing SKUs by revenue and customer reviews.

🔍 Overview

This dashboard provides a 360° view of Amazon product sales, enabling category-level and time-based analysis for data-driven merchandising and inventory decisions. It combines KPI cards, trend visuals, and category breakdowns on a single interactive canvas with quarter-level slicing.

📌 Key Insights
$2.18M in YTD Sales across 28K products sold, generating 19M customer reviews
QTD Sales stand at $811K, tracked against a 4-quarter filter for period-over-period analysis
Men Shoes is the top-growth category — 43.18% YTD growth, contributing $9.40M in sales
Camera leads absolute YTD sales share at 22.62%, followed by Men Clothes at 16.42%
Sales show a strong seasonal ramp from August–December, nearly 3x the Jan–Jul baseline
Top products by YTD sales and by review volume are broken out by product description for SKU-level insight


🛠️ Tools & Techniques
Category	Tools/Techniques Used
Data Modeling	Power BI (Star Schema), Power Query
Calculations	DAX (YTD, QTD, %GT measures)
Visualization	Line charts, bar charts, KPI cards, matrix table
Interactivity	Slicers (Quarter, Product Category)
Design	Custom Amazon-branded theme (black/orange)

📁 Repository Structure
Power_bi_sales/
│
├── dashboard.pbix         # Power BI report file
├── Dataset                # Source dataset used in the dashboard
├── screenshots/           # Dashboard preview images
│   └── dashboard-overview.png
├── LICENSE                # MIT License
└── README.md

🚀 How to View
Clone this repo: git clone https://github.com/Pragspd/Power_bi_sales.git
Open dashboard.pbix in Power BI Desktop (free download from Microsoft)
Use the Product Category dropdown and Quarter checkboxes to explore the data interactively

💡 GitHub can't render .pbix files directly — the screenshot above shows the live dashboard. Open the file in Power BI Desktop for full interactivity.

📈 Dashboard Sections
KPI Summary — YTD Sales, QTD Sales, YTD Products Sold, YTD Reviews
Sales by Month — Trend line showing seasonal sales pattern
Sales by Week — Granular week-by-week revenue tracking
Product Category Table — YTD Sales, %GT YTD Sales, QTD Sales by category
Top Products by Sales & Reviews — Ranked bar charts by product description
