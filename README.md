# Sales Performance Dashboard – Jan 2023 to Dec 2024

## 📊 Overview
This Power BI dashboard visualizes sales performance over time using sample Superstore-style data. It highlights trends by **Month-Year**, **Region**, and **Product Category** with interactive filters.

## ✅ Key Features
- **Monthly Sales Trend (Line Chart)** – Visualizes how sales have changed over time.
- **Sales by Region (Bar Chart)** – Compares total sales across different regions.
- **Sales by Product Category (Donut Chart)** – Shows proportion of sales by product type.
- **Interactive Filter** – Lets users filter the entire dashboard by Category.

## 🛠 Data Preparation
- Created a new calculated column `MonthYear` from `Order Date` using the formula:MonthYear = FORMAT('Superstore_Sample_Sales'[Order Date], "MMM YYYY")
- Used this column as the time axis in the Monthly Sales Trend chart.

## 💡 Insights
1. Sales are in a **downward trend** over the period from **Jan 2023 to Dec 2024**, with a noticeable decline starting **mid-2023**.

2. The **South region leads in total sales**, outperforming other regions like **Central, East, and West**.

3. Sales are **evenly distributed across categories**, with **Furniture slightly leading**, followed by **Technology** and **Office Supplies**.

4. The **West region shows the lowest sales**, indicating potential opportunity or underperformance to investigate.

## 📁 Files Included
- `task8-simple-sales-dashboard-powerbi.pbix` – Power BI project file
- task8-simple-sales-dashboard-powerbi.pdf` – PDF export of the dashboard
- `README.md` – This file

## ⚙️ Tools Used
- Power BI Desktop
