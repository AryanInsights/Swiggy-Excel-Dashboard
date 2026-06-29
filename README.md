# Swiggy Sales Analysis Dashboard

## Project Overview

This project analyzes Swiggy food order data to understand sales performance, customer preferences, regional demand, food type contribution, and time-based ordering trends. The analysis was performed in Microsoft Excel using a cleaned dataset, pivot tables, KPI cards, and dashboard visualizations.

The goal of this project is to convert raw food delivery data into actionable business insights that can help understand revenue patterns, top-performing cities, customer ratings, and demand behavior across months, days, weeks, quarters, and regions.

---

## Dataset

The dataset contains Swiggy order-level food delivery records with the following fields:

- State
- City
- Order Date
- Day
- Quarter
- Week
- Restaurant Name
- Location
- Category
- Dish Name
- Food Type
- Price (INR)
- Rating
- Rating Count

Total records analyzed: **197,430 orders**

---

## Key KPIs

| Metric | Value |
|---|---:|
| Total Sales | ₹53.01M |
| Total Orders | 197.43K |
| Average Rating | 4.34 |
| Total Rating Count | 5.59M |
| Average Order Value | ₹268.51 |

---

## Dashboard Features

The Excel dashboard includes:

- KPI cards for total sales, orders, rating count, average rating, and AOV
- Monthly sales trend analysis
- Daily sales trend analysis
- Quarterly sales comparison
- Veg vs Non-Veg sales distribution
- State-wise sales analysis using map visualization
- Top 5 cities by sales
- Weekly sales trend analysis

---

## Major Insights

### 1. Overall Performance

Swiggy generated total sales of approximately **₹53.01M** from **197.43K orders**, with an average order value of **₹268.51**.

### 2. Food Type Analysis

Veg items contributed the majority of revenue.

| Food Type | Sales |
|---|---:|
| Veg | ₹34.18M |
| Non-Veg | ₹18.83M |

This shows stronger demand for vegetarian food items in the analyzed dataset.

### 3. Monthly Sales Trend

Sales remained fairly consistent across months, with the highest monthly sales coming from:

- January: ₹6.83M
- May: ₹6.79M
- August: ₹6.79M

The dataset shows stable monthly demand without extreme seasonality.

### 4. Daily Sales Trend

Saturday recorded the highest sales among weekdays.

| Day | Sales |
|---|---:|
| Saturday | ₹7.78M |
| Thursday | ₹7.66M |
| Sunday | ₹7.64M |
| Friday | ₹7.58M |
| Wednesday | ₹7.54M |

Weekend and late-week ordering activity appears stronger.

### 5. Quarterly Analysis

| Quarter | Sales | Orders | Average Rating |
|---|---:|---:|---:|
| Q1 | ₹19.67M | 73.10K | 4.34 |
| Q2 | ₹19.90M | 74.16K | 4.34 |
| Q3 | ₹13.44M | 50.17K | 4.34 |

Q2 had the highest sales and order volume.

### 6. Top Cities by Sales

| Rank | City | Sales |
|---:|---|---:|
| 1 | Bengaluru | ₹5.46M |
| 2 | Lucknow | ₹3.12M |
| 3 | Hyderabad | ₹3.02M |
| 4 | Mumbai | ₹3.02M |
| 5 | New Delhi | ₹2.83M |

Bengaluru is the strongest-performing city in the dataset.

### 7. State-Wise Performance

Top-performing states include:

- Karnataka
- Uttar Pradesh
- Telangana
- Maharashtra
- Delhi
- Gujarat
- Punjab

Karnataka leads overall sales performance, driven mainly by Bengaluru.

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- KPI Cards
- Data Cleaning
- Dashboard Design
- Exploratory Data Analysis

---

## Project Workflow

1. Imported raw Swiggy order data into Excel
2. Cleaned and structured the dataset
3. Created calculated columns for:
   - Day
   - Quarter
   - Week
   - Food Type
4. Built pivot tables for sales, ratings, orders, food type, city, state, month, week, and quarter analysis
5. Created an interactive dashboard using charts and KPI cards
6. Extracted insights from the dashboard

---

## Business Recommendations

- Focus marketing campaigns in high-performing cities such as Bengaluru, Lucknow, Hyderabad, Mumbai, and New Delhi.
- Promote vegetarian food categories since Veg items contribute the majority of sales.
- Use weekend-focused offers, especially on Saturdays, to maximize order volume.
- Investigate lower-performing states and cities to identify supply gaps, pricing issues, or limited restaurant coverage.
- Maintain customer satisfaction by monitoring ratings and rating count trends regularly.

---

## Future Improvements

- Add slicers for city, state, restaurant, food type, and quarter
- Build category-level analysis for dishes and restaurant performance
- Add customer segmentation if customer-level data becomes available
- Create a Power BI version of the dashboard
- Add forecasting for future sales trends
- Analyze delivery time, discounts, and customer retention if more data is available

---

## Conclusion

This Swiggy Sales Analysis project demonstrates how Excel can be used to transform raw food delivery data into meaningful business insights. The dashboard highlights key performance metrics, sales trends, regional demand, food preferences, and city-wise contribution, making it useful for business decision-making and portfolio presentation.
