# 📊 Sales Performance Dashboard

## 📌 Project Overview
The **Sales Performance Dashboard** is an interactive Power BI project designed to analyze sales data and provide valuable business insights. The dashboard helps stakeholders monitor revenue, product performance, customer behavior, salesperson productivity, payment preferences, and product returns.

---

## 🎯 Project Objectives

- Analyze overall sales performance.
- Monitor product-wise sales and quantity sold.
- Compare sales across different payment methods.
- Evaluate salesperson performance.
- Track returned products.
- Support data-driven business decisions.

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV Dataset

---

## 📈 Key Metrics

| KPI | Value |
|------|------|
| Total Revenue | 4.38M |
| Total Unit Price | 448.24K |
| Total Quantity Sold | 16K |

---

## 📊 Dashboard Features

### 1️⃣ Sales Overview
- Total Revenue
- Total Quantity Sold
- Total Unit Price

### 2️⃣ Product Analysis
- Quantity Sold by Product
- Revenue by Product
- Product Return Analysis

### 3️⃣ Customer Analysis
- Sales by Customer Type
  - Retail
  - Wholesale

### 4️⃣ Salesperson Performance
- Sales contribution by salesperson
- Performance comparison

### 5️⃣ Payment Method Analysis
- Cash
- Credit Card
- Debit Card
- Gift Card
- Online Payments

### 6️⃣ Regional Analysis
- Quantity Sold by Product and Region
- Regional sales distribution

### 7️⃣ Interactive Filters
Users can filter data by:
- Product
- Customer Type
- Payment Method
- Region

---

## 📂 Dataset Columns

| Column | Description |
|----------|------------|
| Product | Product Name |
| Quantity | Units Sold |
| UnitPrice | Price Per Unit |
| TotalPrice | Total Revenue |
| CustomerType | Retail / Wholesale |
| Salesperson | Sales Representative |
| PaymentMethod | Mode of Payment |
| Region | Sales Region |
| Returned | Return Status |

---

## 🔄 Data Preparation Process

1. Imported raw sales data into Power BI.
2. Cleaned and transformed data using Power Query.
3. Handled missing values and duplicates.
4. Created DAX measures for KPI calculations.
5. Designed interactive dashboard visuals.
6. Added slicers and filters.
7. Generated business insights.

---

## 📷 Dashboard Preview

### Dashboard Page 1
- KPI Cards
- Customer Type Analysis
- Product Quantity Distribution
- Salesperson Performance
- Payment Method Analysis

### Dashboard Page 2
- Sales Overview
- Product Return Analysis
- Regional Analysis
- Payment Method Performance

---

## 📌 Sample DAX Measures

```DAX
Total Revenue = SUM(Sales[TotalPrice])

Total Quantity = SUM(Sales[Quantity])

Average Unit Price = AVERAGE(Sales[UnitPrice])

Total Returns = COUNT(Sales[Returned])
```

---

## 💡 Business Insights

- Identified top-selling products.
- Compared sales across payment methods.
- Evaluated salesperson effectiveness.
- Tracked return trends.
- Analyzed customer purchasing behavior.
- Identified regional sales opportunities.

---

## 🚀 Business Value

This dashboard helps organizations:

- Monitor sales performance efficiently.
- Improve inventory management.
- Optimize sales strategies.
- Increase operational efficiency.
- Make data-driven decisions.

---

## 👨‍💻 Author

**Kirthick**  
🎓 B.Com Business Analytics Student  
📊 Aspiring Data Analyst

### Skills Demonstrated
- Power BI
- Data Cleaning
- Data Visualization
- DAX
- Business Intelligence
- Dashboard Design
- Data Analysis

---

⭐ If you like this project, don't forget to **Star** the repository!
