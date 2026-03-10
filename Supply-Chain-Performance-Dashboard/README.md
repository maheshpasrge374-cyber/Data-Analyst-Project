📦 Supply Chain Performance Dashboard (Power BI)

An interactive Power BI dashboard designed to analyze supply chain operations with a focus on delivery performance, sales trends, and profitability across regions and customer segments.

The dashboard helps identify operational inefficiencies such as late deliveries, fulfillment delays, and sales losses, while also providing insights into regional sales performance and customer segmentation.

📌 Project Overview

Efficient supply chain management is critical for maintaining customer satisfaction and profitability. This dashboard transforms raw supply chain data into actionable insights that help stakeholders:

Monitor delivery performance

Identify operational bottlenecks

Analyze sales distribution across regions and customer segments

Evaluate the impact of shipping methods on delivery outcomes

Track profitability across markets and departments

The report is organized into two analytical views:

Delivery Performance Dashboard

Sales Performance Dashboard

📊 Dataset

The dataset used in this project is sourced from Kaggle:

Dataco Smart Supply Chain Dataset for Big Data Analysis

https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis/data

This dataset contains supply chain transaction data including:

Order information

Shipping details

Delivery status

Customer segments

Regional sales

Profit and loss metrics

📦 Delivery Performance Dashboard
<p align="center"> <img src="supplychain_main_directory/assets/Delivery Performance.png" width="900"/> </p>
Key Visuals
1️⃣ Delivery Status by Order Count

Displays the distribution of delivery outcomes including:

Late deliveries

On-time shipments

Advance shipping

Cancelled orders

Key Insight

Approximately 55% of deliveries are late, indicating potential inefficiencies in the supply chain fulfillment process.

2️⃣ Top Regions with Sales Losses

Highlights regions experiencing the highest sales losses due to:

Order cancellations

Shipping delays

On-hold orders

Key Insight

Western Europe and Central America show the highest levels of sales loss.

3️⃣ Shipping Mode vs Delivery Status

Compares shipping methods such as:

First Class

Second Class

Standard Class

Same Day

Key Insight

First Class shipping shows a higher frequency of late deliveries, while Same Day shipping performs significantly better for on-time delivery.

4️⃣ Order Profits vs Fulfillment Time

Analyzes the relationship between order-to-ship time and profitability.

Key Insight

Orders with shorter fulfillment times generally produce higher profits, while longer delays reduce overall profitability.

5️⃣ Average Days for Shipping by Delivery Status

Compares:

Scheduled shipping days

Actual shipping days

Order fulfillment time

Key Insight

Late deliveries are associated with longer fulfillment times, confirming operational delays.

💰 Sales Performance Dashboard
<p align="center"> <img src="supplychain_main_directory/assets/Sales and Customers.png" width="900"/> </p>
Key Visuals
1️⃣ Sales by Region and Customer Segment

Displays sales distribution across:

Geographic regions

Customer segments (Consumer, Corporate, Home Office)

Key Insight

Western Europe and Central America dominate sales, with the Consumer segment contributing the highest revenue.

2️⃣ Profits by Market and Department

Breaks down profitability across:

Markets (LATAM, Europe, etc.)

Product departments such as Apparel and Fitness.

Key Insight

LATAM and Europe generate the highest profits, with Apparel and Fan Shop departments performing strongly.

3️⃣ Sales by Payment Type and Late Delivery Risk

Examines the relationship between payment methods and delivery outcomes.

Key Insight

Orders paid using Debit show the highest rate of late deliveries, indicating a possible operational pattern worth investigating.

🛠 Tools Used

Power BI Desktop

DAX (Data Analysis Expressions)

Kaggle Supply Chain Dataset

Data modeling and visual analytics

![Delivery Performance](./assets/Delivery_Performance.png) 

 
![Sales and Customers](./assets/Sales_and_Customers.png)

📁 Repository Structure

 ── supplychain_main_directory
│   │
│   ├── Supply_Chain_Dashboard.pbix
│   │
│   └── assets
│       ├── Delivery Performance.png
│       └── Sales and Customers.png
│
└── README.md


🔮 Future Enhancements

Potential improvements for this project include:

> Integrating predictive analytics to forecast delivery delays

> Adding machine learning models for delay risk prediction

> Incorporating customer satisfaction feedback data

> Building additional dashboards for inventory and logistics optimization


📫 Author

Mahesh P
📧 maheshpasarge08@gmail.com