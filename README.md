📊 Mobile Sales Analysis (Power BI)

📌 Project Overview

This project showcases an interactive **Mobile Sales Dashboard** built entirely in **Power BI**. It provides a comprehensive view of sales performance, customer insights, product trends, and payment behaviors using dynamic and visually rich reports.

🛠️ Tool Used

* Power BI (Data Modeling, Visualization, Dashboard Design)

📂 Dataset Description

The dataset contains mobile sales transaction data with the following fields:

* Transaction ID – Unique identifier for each transaction
* Day, Month, Year, Day Name – Time-based attributes
* Brand – Mobile brand (e.g., Apple, Samsung, Xiaomi)
* Mobile Model – Specific phone model
* Units Sold – Number of units sold
* Price Per Unit – Price of each unit
* Customer Name – Name of the customer
* Customer Age – Age of the customer
* City – Customer location
* Payment Method – UPI, Cash, Credit Card, Debit Card
* Customer Ratings – Rating given by the customer

⚙️ Data Modeling & Measures

Data was modeled within Power BI using calculated columns and measures.

Example measure:

DAX id="a8v2k1"
Total Sales = SUMX(Sales_Data, Sales_Data[Units Sold] * Sales_Data[Price Per Unit])


Other key calculations:

* Total Quantity
* Total Transactions
* Average Sales Value

📈 Dashboard Features

🔑 KPI Cards

* Total Sales: 769M
* Total Quantity Sold: 19K
* Total Transactions: 4K
* Average Sales Value: 40K

📊 Visualizations

* Sales Trend by Month (Line Chart)
* Sales by Day Name
* Sales by Mobile Model
* Sales by Brand (Table)
* Transactions by Payment Method (Pie Chart)
* Customer Ratings Distribution
* Sales by City

🎛️ Filters / Slicers

* Mobile Model
* Brand
* Payment Method
* Day Name
* Month Selection

🔍 Key Insights

* Sales show fluctuations across months with noticeable peaks
* Top mobile models contribute significantly to total revenue
* Payment methods are evenly distributed among customers
* Customer ratings are mostly positive (4–5 range)
* Sales performance varies by city

🎯 Key Learnings

* Building interactive dashboards in Power BI
* Creating DAX measures and calculated columns
* Designing user-friendly layouts with slicers and KPIs
* Turning raw data into meaningful business insights

🚀 Future Enhancements

* Add forecasting for sales trends
* Create drill-through reports for detailed analysis
* Enhance UI/UX with advanced visuals and tooltips
* Include additional KPIs like growth rate and segmentation

👤 Author

Varun Sirohi
