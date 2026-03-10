📊 Sales Performance Dashboard (Power BI)

An interactive executive-style Power BI dashboard designed to analyze e-commerce sales performance across multiple product categories, regions, and time periods.

This project demonstrates how raw sales data can be transformed into actionable business insights through data modeling, DAX calculations, and effective visual storytelling.

📌 Project Overview

The objective of this project is to provide stakeholders with a clear and comprehensive view of sales performance. The dashboard enables users to track revenue trends, evaluate regional performance, and identify high-performing product categories through dynamic KPIs and interactive visualizations.

This project highlights practical skills in:

Business intelligence reporting

Data modeling and relationships

DAX-based calculations

Interactive dashboard design

Data-driven decision support

🔍 Key Features
Dynamic KPI Metrics

Total Revenue

Total Orders

Quantity Sold

Average Order Value (AOV)

Units per Order

Price per Unit

Interactive Filters

Users can dynamically filter the dashboard using:

Year

Month

Region

Product

Category

Revenue Trend Analysis

A line chart visualizes revenue performance over time, enabling quick identification of trends and seasonal patterns.

Regional & Category Performance

Bar charts and donut charts provide insights into:

Sales contribution by region

Product category performance

Custom DAX Measures

Business logic is implemented using DAX (Data Analysis Expressions) to ensure accurate calculations and scalable analytics.

Professional Dashboard Layout

The dashboard features a clean, executive-style layout with modern KPI cards displaying full numeric values without abbreviations.

Time Intelligence

A dedicated date dimension table enables time-based analysis such as monthly and yearly revenue trends.

🗂 Data Model

The dashboard follows a simple star schema design.

Fact Table

data/sales_data.csv

Contains transactional sales data including:

Order information

Product details

Region

Revenue

Quantity sold

Dimension Table

data/date_table.csv

A dedicated calendar table used for:

Year and month filtering

Time intelligence calculations

Trend analysis

A relationship is established between the sales dataset and the date table to support accurate time-based reporting.

📸 Dashboard Preview
<p align="center"> <img src="assets/dashboard_preview.png" width="900"/> </p>
📈 Example Business Insights

Using this dashboard, stakeholders can quickly identify:

Top-performing regions contributing the highest revenue

Product categories generating the most sales

Monthly revenue trends and potential seasonal patterns

Average order value and customer purchasing behavior

Underperforming regions that may require strategic attention

🛠 Tools Used

Power BI Desktop

DAX (Data Analysis Expressions)

CSV-based simulated sales dataset

Data modeling and relationships

Custom report formatting and theming

📁 Repository Structure
sales-performance-dashboard-pbi
│
├── Sales_Dashboard.pbix
├── README.md
│
├── data
│   ├── sales_data.csv
│   └── date_table.csv
│
└── assets
    └── dashboard_preview.png
📂 Data Sources

The project uses simulated e-commerce sales data stored in CSV format.

data/sales_data.csv – Transaction-level sales dataset

data/date_table.csv – Date dimension table used for time intelligence calculations

📫 Author

Mahesh P
📧 maheshpasarge08@gmail.com