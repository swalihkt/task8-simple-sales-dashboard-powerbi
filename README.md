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
1. Sales followed a **downward trend** from early 2023 to the end of 2024.
2. The **South region** had the highest overall sales during this period.
3. **Technology** slightly outperformed other categories in total sales.
4. The **West region** recorded the **lowest sales**, signaling potential improvement areas.

## 📁 Files Included
- `Sales_Performance_Dashboard.pdf` – PDF export of the Power BI dashboard
- `README.md` – This file

## ⚙️ Tools Used
- Power BI Desktop
