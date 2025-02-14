# WAREHOUSE_AND_RETAIL_SALES_ANALYSIS_ON_PYTHON
The dataset tracks sales and inventory transactions for beverages(liquor, wine, beer) and related supplies across retail and warehouse channels. It helps analyze sales performance, supplier relationship and inventory adjustment. The dataset was sourced from data.gov with the name ‘Warehouse_and_Retail_Sales.csv’.  
# Project Overview
This project explores sales performance and inventory transactions across retail and warehouse channels using Exploratory Data Analysis (EDA). The dataset, sourced from data.gov, contains 307,645 rows and covers sales data for wine, liquor, beer, and related supplies.
# Key Findings
Top Supplier: 🏆 Republic National Distributing Co.
Most Sold Product Type: 🍷 Wine (61.0%) followed by 🥃 Liquor (21.8%).
Sales Insights:
Highest single-month sales: 📅 July 2020 (70.2% warehouse sales).
Most profitable year: 📊 2019 had the highest total sales.
Total Sales:
Retail Sales: $2.16M
Retail Transfers: $2.13M
Warehouse Sales: $7.78M
Data Anomalies: 716 entries had negative warehouse sales, likely due to returns or adjustments.
# Dataset Overview
The dataset includes time-based sales records (Year, Month), supplier details, item descriptions, product categories (Wine, Liquor, Beer, etc.), and sales figures (Retail Sales, Retail Transfers, Warehouse Sales). The dataset helps analyze sales trends, supplier relationships, and inventory adjustments.
# Data Cleaning & Transformation
Missing Values: Supplier names were missing for some rows and replaced with "Unknown".
Negative Sales: Identified and analyzed for potential returns or corrections.
Duplicates: No duplicate rows detected.
#  Exploratory Data Analysis (EDA)
Top Suppliers Analysis: Found leading suppliers using value_counts().
Monthly Sales Trends: Identified peak sales months with groupby().
Sales Distribution: Right-skewed, indicating most transactions are small, with a few high-value ones.
Correlation Analysis: Found strong relation between retail sales & transfers but weak relation with warehouse sales.
#  Visualizations
📊 Pie Chart: Sales distribution by product type.
📉 Histogram: Retail sales distribution (right-skewed).
📊 Bar Chart: Top suppliers with most transactions.
📈 Line Chart: Sales trends over time, highlighting seasonal spikes.
🗺️ Heatmap: Strong correlation between retail sales & transfers.
# Business Insights & Recommendations
✅ Warehouse Sales Drive Revenue – Suggests focus on bulk sales.
✅ Investigate Negative Sales – Determine reasons for returns or adjustments.
✅ Supplier Optimization – Analyze performance of top suppliers to improve inventory management.
✅ Promotional Strategies – Explore discounts and campaigns for wine & liquor to maximize revenue.
# Technologies Used
Python 🐍 (pandas, NumPy) – Data Manipulation
Matplotlib & Seaborn 📊 – Data Visualization
# Next Steps
Deep dive into negative sales to confirm impact on revenue.
Optimize supplier relationships for cost efficiency.
Develop targeted marketing campaigns for high-selling categories.

