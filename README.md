Sales Performance Dashboard - Power BI
📊 Project Overview

This project presents an interactive Sales Performance Dashboard developed using Power BI to analyze sales data across products, customer types, payment methods, salespersons, and regions.

The dashboard helps businesses monitor key sales metrics, identify top-performing products, evaluate salesperson performance, and understand customer purchasing patterns through visually appealing reports.

🎯 Objectives
Analyze overall sales performance.
Track product-wise sales and quantity sold.
Compare sales across different payment methods.
Evaluate salesperson performance.
Monitor product return trends.
Support data-driven business decisions.
🛠️ Tools & Technologies
Power BI Desktop
Microsoft Excel / CSV Dataset
Power Query
DAX (Data Analysis Expressions)
📈 Key Performance Indicators (KPIs)
KPI	Value
Total Sales Revenue	4.38M
Total Unit Price	448.24K
Total Quantity Sold	16K
📊 Dashboard Features
1. Sales Overview
Total Revenue
Total Quantity Sold
Total Unit Price
2. Product Analysis
Quantity Sold by Product
Total Sales by Product
Product-wise Return Analysis
3. Customer Analysis
Sales Distribution by Customer Type
Retail
Wholesale
4. Salesperson Performance
Sales contribution of each salesperson
Ranking based on sales value
5. Payment Method Analysis
Cash
Credit Card
Debit Card
Gift Card
Online Payment
6. Regional Analysis
Quantity Sold by Product and Region
Regional sales contribution
7. Interactive Filtering

Users can filter dashboard data using:

Product Selection
Customer Type
Payment Method
Region
📌 Insights Generated
Identified top-selling products.
Compared revenue generated through various payment methods.
Evaluated salesperson efficiency.
Tracked product return percentages.
Analyzed customer purchasing behavior.
Discovered regional sales trends.
📂 Dataset Information

The dataset contains:

Column Name	Description
Product	Product Name
Quantity	Units Sold
UnitPrice	Price per Unit
TotalPrice	Total Revenue
CustomerType	Retail/Wholesale
Salesperson	Sales Representative
PaymentMethod	Mode of Payment
Region	Sales Region
Returned	Product Return Status
🔄 Data Processing Steps
Imported raw sales dataset into Power BI.
Cleaned and transformed data using Power Query.
Removed duplicates and handled missing values.
Created calculated measures using DAX.
Built interactive visualizations.
Added slicers and filters for dynamic analysis.
Published dashboard for reporting.
📷 Dashboard Preview
Dashboard Page 1
KPI Cards
Customer Type Analysis
Product Quantity Distribution
Salesperson Performance
Payment Method Analysis
Dashboard Page 2
Sales Performance Overview
Product Return Analysis
Regional Product Analysis
Revenue Trend by Payment Method
📊 Sample DAX Measures
Total Sales = SUM(Sales[TotalPrice])

Total Quantity = SUM(Sales[Quantity])

Average Unit Price = AVERAGE(Sales[UnitPrice])

Total Returns = COUNT(Sales[Returned])
🚀 Business Value

This dashboard enables stakeholders to:

Monitor sales performance in real-time.
Improve inventory planning.
Identify high-performing products.
Optimize sales strategies.
Enhance customer satisfaction.
Support strategic business decisions.
👨‍💻 Author

Kirthick Pounraj
B.Com Business Analytics Student
Aspiring Data Analyst

Skills Demonstrated
Data Cleaning
Data Visualization
Power BI
DAX
Business Intelligence
Dashboard Design
Data Analysis
