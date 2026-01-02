# FUTURE_DS_01


Superstore Sales Performance Dashboard: 
A visual overview of key sales metrics, product trends, and regional performance for a retail superstore.

Purpose: 
To help business stakeholders monitor sales performance, identify top-selling products and regions, and optimize shipping and inventory decisions using data-driven insights.

Tech Stack:
The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main data visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.

Data Source: 
https://www.kaggle.com/datasets/mohamed38/superstoredataset 
It is a sample dataset from Kaggle about a superstore's sales

Features: 

Business Problem - Lack of visibility into sales trends, product performance, and regional shipping efficiency.

Goal of Dashboard - Provide actionable insights to improve profitability, streamline operations, and support strategic decisions.

Walkthrough of Dashboard - A breakdown of each visual component and its purpose: 
  - Top Metrics (KPIs)
    Type: Numeric Cards
    Purpose: Quickly communicate high-level performance indicators like total sales, profit, quantity, and orders.
    Why: Cards offer instant visibility and are ideal for summarizing key figures.
  - Shipment Delivery by Ship Mode
    Type: Bar Chart
    Purpose: Show distribution of shipments across different delivery modes.
    Why: Bar charts are effective for comparing categorical data like ship modes.
  - Top 5 States with Best Sales
    Type: Stacked Bar Chart
    Purpose: Compare total sales across top-performing states and ship modes.
    Why: Stacked bars allow simultaneous comparison of state-wise performance and shipping preferences.
  - Top 5 Best-Selling Products
    Type: Horizontal Bar Chart
    Purpose: Highlight products generating the highest revenue.
    Why: Horizontal bars are ideal for ranking items with long names and clear comparisons.
  - Sales and Profit by Sub-Category
    Type: Grouped Bar Chart
    Purpose: Compare both sales and profit across product sub-categories.
    Why: Grouped bars enable side-by-side comparison of two metrics for each category.
  - Sales by Segment
    Type: Donut Chart
    Purpose: Visualize proportion of sales from Consumer, Corporate, and Home Office segments.
    Why: Donut charts are intuitive for showing percentage breakdowns of a whole.
  - Ship Mode by Month and Region
    Type: Clustered Bar Chart
    Purpose: Analyze monthly shipping trends across regions.
    Why: Clustered bars help visualize temporal and regional patterns in one view.

Business Impact & Insights - 
- California leads in sales, suggesting strong regional demand.
- Standard Class dominates shipping, indicating cost-effective delivery preference.
- Phones and Chairs are top revenue drivers, guiding inventory and marketing focus.
- Consumer segment contributes 50% of sales, highlighting a key customer base.
- Monthly and regional shipping trends reveal operational bottlenecks and optimization opportunities.

Screenshot: 
