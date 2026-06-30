# 🍔 Swiggy Analysis Dashboard — Excel

> An end-to-end data analysis and visualization project built on Swiggy food delivery order data, covering **1,97,430 orders** across **28 states**, **993 restaurants**, and **59,064 dishes** in India (Jan–Aug 2025).

---

## 🖼️ Dashboard Preview

![image alt](https://github.com/AryanInsights/Swiggy-Excel-Dashboard/blob/22a8a360abee9d01d3bfa43c48a5f710767e5524/Snapshot%20of%20Swiggy%20Dashboard.png)

---

## 📌 Project Overview

This Excel dashboard analyzes Swiggy's order-level data across India, using **PivotTables**, **PivotCharts**, and **KPI cards** to surface trends in sales, ratings, food preferences, and regional performance — all in a single interactive, slicer-driven dashboard.

| KPI | Value |
|---|---|
| 💰 Total Sales | ₹5,30,12,505.77 (~₹5.3 Cr) |
| 📦 Total Orders | 1,97,430 |
| ⭐ Average Rating | 4.34 / 5.0 |
| 🗳️ Total Rating Count | 55,91,574 |
| 💵 Average Order Value (AOV) | ₹268.51 |
| 🏪 Total Restaurants | 993 |
| 🗺️ States Covered | 28 |
| 🍽️ Unique Dishes | 59,064 |

---

## 🗂️ Data Structure

The workbook contains **3 sheets**:

| Sheet | Purpose |
|---|---|
| `Swiggy Data` | Raw transactional dataset (1,97,430 rows) |
| `Analysis` | PivotTables powering all dashboard visuals |
| `Dashboard` | Final interactive dashboard view |

### 📋 Raw Data Columns (`Swiggy Data`)

| Column | Type | Description |
|---|---|---|
| State | Text | Indian state of the order |
| City | Text | City of delivery |
| Order Date | Date | Date the order was placed |
| Days | Text | Day of week (Mon–Sun) |
| Quarter | Text | Quarter of the year (Q1–Q3) |
| Week | Number | Week number (1–36) |
| Restaurant Name | Text | Name of the restaurant |
| Location | Text | Restaurant's locality |
| Category | Text | Menu category (Starters, Main Course, etc.) |
| Dish Name | Text | Name of the ordered dish |
| Food Type | Text | Veg / Non-Veg |
| Price (INR) | Number | Order price in ₹ |
| Rating | Decimal | Dish rating (0–5) |
| Rating Count | Number | Number of ratings received |

---

## 📊 Dashboard Components (PivotTables)

### 1. KPI Summary Cards
Total Sales, Average Rating, Total Rating Count, Order Count, and AOV — calculated using `SUM`, `AVERAGE`, and `COUNT` pivot aggregations.

### 2. Monthly Trend
Sales broken down Jan → Aug, showing month-over-month order value fluctuation.

| Month | Sales (₹) |
|---|---|
| Jan | 68,25,186 |
| Feb | 62,69,106 |
| Mar | 65,73,530 |
| Apr | 65,94,515 |
| May | 67,93,558 |
| Jun | 65,14,183 |
| Jul | 66,50,966 |
| Aug | 67,91,462 |

### 3. Food Type Split (Veg vs Non-Veg)

| Food Type | Orders | Sales (₹) |
|---|---|---|
| 🥦 Veg | 1,39,546 | 3,41,80,398 |
| 🍗 Non-Veg | 57,884 | 1,88,32,108 |

> Veg orders dominate at **71%** of total order volume and **64%** of total sales.

### 4. Daily Trend
Order value distribution across all 7 days of the week (Mon–Sun), showing fairly even demand with a slight weekend peak (Sat: ₹77.8L).

### 5. Quarterly Analysis
| Quarter | Sales (₹) | Avg Rating | Orders |
|---|---|---|---|
| Q1 | 1,96,67,822 | 4.34 | 73,096 |
| Q2 | 1,99,02,257 | 4.34 | 74,163 |
| Q3 | 1,34,42,427 | 4.34 | 50,171 |

### 6. State-wise Analysis
Sales broken down across all 28 states. Top performer: **Karnataka** (₹54.6L), followed by Telangana, Maharashtra, and Uttar Pradesh.

### 7. Top 5 Cities by Sales

| Rank | City | Sales (₹) |
|---|---|---|
| 🥇 | Bengaluru | 54,56,798 |
| 🥈 | Lucknow | 31,17,360 |
| 🥉 | Hyderabad | 30,21,712 |
| 4 | Mumbai | 30,15,573 |
| 5 | New Delhi | 28,29,181 |

### 8. Weekly Sales Trend
Week-by-week sales (Week 1–36) used to power a line chart showing consistent demand (~₹15L/week) with minor seasonal dips.

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Microsoft Excel** | Data analysis & dashboard creation |
| **PivotTables** | Aggregating sales, ratings, and order metrics |
| **PivotCharts** | Visualizing monthly, daily, and quarterly trends |
| **Slicers** | Interactive filtering by State, Food Type, Category |
| **Excel Formulas** | AOV, growth %, and summary KPI calculations |

---

## 📊 Key Insights

- 🥦 **Veg dishes** dominate orders (71%) and revenue (64%) over Non-Veg
- 🏙️ **Bengaluru** is the top-performing city by sales, nearly **2x** the next closest city
- 📈 **Q2** was the strongest quarter by sales (₹1.99 Cr), while Q3 data covers only 2 months (Jul–Aug)
- ⭐ **Average rating stays consistently around 4.34** across all quarters — strong customer satisfaction
- 📅 **Saturday** sees the highest single-day sales, suggesting weekend ordering peaks
- 🍽️ **"Recommended"** is by far the most ordered category (24,100 orders), followed by Main Course and Desserts
- 🗺️ **Karnataka** leads state-wise sales, driven heavily by Bengaluru's order volume

---

👤 Author

Aryan Kumar


📧 Email: aryankumar.ak929@gmail.com
💼 LinkedIn: https://www.linkedin.com/in/aryankumar4
🐙 GitHub: https://github.com/AryanInsights


---

## 📄 License

This project is for educational and portfolio purposes only.

Data used is synthetic/sample data and does not represent real Swiggy transaction information.

---

⭐ **If you found this project helpful, give it a star!**
