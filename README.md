# 📊 Mobile Sales Analysis (Power BI)

## 📌 Project Overview

This project presents an interactive **Mobile Sales Dashboard** built using **Power BI**. It transforms raw sales data into meaningful insights, helping analyze sales performance, customer behavior, product trends, and payment patterns through visually rich reports.


## 🛠️ Tools & Technologies

* **Power BI** – Data Modeling, Visualization, Dashboard Design
* **DAX (Data Analysis Expressions)** – Measures and Calculations


## 📂 Dataset Description

The dataset contains mobile sales transaction data with the following attributes:

* **Transaction ID** – Unique identifier for each transaction
* **Date Fields** – Day, Month, Year, Day Name
* **Brand** – Mobile brands (Apple, Samsung, Xiaomi, etc.)
* **Mobile Model** – Specific phone model
* **Units Sold** – Number of units sold
* **Price Per Unit** – Selling price
* **Customer Name** – Customer identity
* **Customer Age** – Age group analysis
* **City** – Customer location
* **Payment Method** – UPI, Cash, Credit Card, Debit Card
* **Customer Ratings** – Feedback score (1–5)


## ⚙️ Data Modeling & DAX Measures

### Example Measure:

```DAX
Total Sales = SUMX(Sales_Data, Sales_Data[Units Sold] * Sales_Data[Price Per Unit])
```

### Other Key Measures:

* Total Quantity Sold
* Total Transactions
* Average Sales Value


## 📈 Dashboard Features

### 🔑 KPI Cards

* **Total Sales:** 769M
* **Total Quantity Sold:** 19K
* **Total Transactions:** 4K
* **Average Sales Value:** 40K

### 📊 Visualizations

* Sales Trend by Month (Line Chart)
* Sales by Day Name
* Sales by Mobile Model
* Sales by Brand (Table)
* Transactions by Payment Method (Pie Chart)
* Customer Ratings Distribution
* Sales by City

### 🎛️ Filters / Slicers

* Mobile Model
* Brand
* Payment Method
* Day Name
* Month Selection

## 🔍 Key Insights

* Sales fluctuate across different months with noticeable peaks
* Top-performing mobile models contribute the majority of revenue
* Payment methods are evenly distributed among customers
* Customer ratings are mostly positive (4–5 range)
* Sales performance varies across cities

## 🎯 Key Learnings

* Building interactive dashboards in Power BI
* Creating DAX measures and calculated columns
* Designing user-friendly layouts with slicers and KPIs
* Converting raw data into actionable business insights

## 🚀 Future Enhancements

* Add sales forecasting
* Implement drill-through reports
* Improve UI/UX with advanced visuals
* Include KPIs like growth rate and customer segmentation

## 👤 Author

**Varun Sirohi**


