# Sales Analytics Dashboard 

An interactive Power BI dashboard developed to analyze sales performance, monitor profitability, identify business trends, and generate actionable insights that support data-driven business decisions.

# Introduction

Sales data plays a vital role in understanding business performance and identifying opportunities for growth. However, raw transactional data often makes it difficult to recognize trends, compare performance, or evaluate profitability.

This project presents a **Sales Analytics Dashboard** built using many visualisation tools like Microsoft Power BI,Power Query Editor etc. transforming raw sales records into interactive and meaningful visualizations. The dashboard enables users to monitor sales, profit, returns, and customer purchasing behavior across different regions, categories, and time periods, allowing businesses to make informed strategic decisions.

# Business Problem Statement

Retail companies generate large volumes of sales data every day. However, without proper analysis, it becomes difficult to understand which products generate the highest revenue, which regions perform best, why profits fluctuate despite increasing sales, or how product returns affect business performance.

This dashboard converts raw transactional sales data into meaningful business insights, enabling decision-makers to evaluate sales performance, improve profitability, optimize inventory, and enhance customer satisfaction.

# Business Questions

The dashboard answers the following business questions:

- What is the total sales revenue generated?
- What is the overall profit earned ?
- Which products generate the highest sales?
- Why profits were less when Sales revenue had good growth spike?
- Which categories contribute the highest revenue?
- Which customer segment generates the most sales?
- Which regions and states perform best?
- What is the overall product return rate?
- How do sales and profit change over time?
- What is the expected sales forecast for upcoming months?

  
# Project Objective

The objective of this project is to provide a comprehensive overview of business performance by:

- Monitoring sales and profit trends.
- Tracking customer purchasing behavior.
- Identifying top-performing and low-performing products.
- Comparing regional and category-wise performance.
- Analyzing product returns and profitability.
- Supporting better inventory and business decisions.

# Solution Approach 

## 1. Data Collection & Preparation

- Imported the sales dataset into **Microsoft Power BI Desktop**.
- Performed initial data exploration using **Power Query Editor**.
- Inspected the dataset using **Column Quality**, **Column Distribution**, and **Column Profile**.
- Changed the profiling option to **Based on Entire Dataset** for comprehensive analysis.
- Cleaned and transformed the dataset by handling missing values, validating data types, and removing inconsistencies to ensure data accuracy.

---

## 2. Data Modeling

- Built an optimized data model by establishing relationships between the required tables.
- Created a dedicated **Date Table** to enable advanced time intelligence calculations.
- Structured the data model to support efficient filtering, aggregation, and report performance.

---

## 3. DAX Calculations & KPI Development

Developed business-driven DAX measures to monitor key performance indicators, including:

- Total Sales
- Total Profit
- Profit Margin (%)
- Average Delivery Days

Additionally, implemented advanced DAX calculations using functions such as:

- `CALCULATE()`
- `SUM()`
- `DIVIDE()`
- `FILTER()`

These measures enabled dynamic business analysis, KPI tracking, and time-based calculations across the dashboard.

---

## 4. Dashboard Development

Designed multiple interactive report pages to provide comprehensive business insights, including:

- Sales by Ship Mode
- Sales by Category
- Top Sales by Sub-Category
- Monthly Sales (Year-over-Year)
- Monthly Profit (Year-over-Year)
- Regional Sales Analysis
- City-wise Sales Analysis
- Payment Mode Analysis
- Return Rate Analysis
- Loss Analysis by Product Sub-Category
- State-wise Sales Performance

Each visualization was designed to help users quickly identify trends, compare performance, and support data-driven decision-making.

---

## 5. Sales Forecasting

Developed a **30-Day Sales Forecast** using Power BI's forecasting capabilities to estimate future sales trends based on historical performance, enabling better planning and proactive business decisions.

---

## 6. User Experience & Interactivity

Enhanced the overall user experience by implementing:

- Interactive Slicers
- Cross-Filtering
- Responsive Visual Interactions
- Consistent Dashboard Theme
- Professional Color Palette
- Clean Layout and Formatting

These features allow users to seamlessly explore data across multiple business dimensions.

---

## 7. Final Report Optimization

- Optimized dashboard performance for smooth interaction.
- Ensured consistency across all report pages through standardized formatting and visual design.
- Delivered a professional, interactive Power BI dashboard that provides actionable business insights through an intuitive user interface.

# Technologies Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV
- Data Modeling


# Dashboard Features

- Interactive KPI Cards
- Dynamic Year and Month Filters
- Sales Forecasting
- Profitability Analysis
- Return Rate Analysis
- Customer Segment Analysis
- Product Performance Analysis
- Regional Sales Analysis
- Category & Sub-Category Performance
- Monthly Sales Trend
- Interactive Drill-down Visuals

### Visualizations Used

- Line Chart for Monthly Sales Trend and Forecast
- Clustered Column Chart for Sales vs Profit Comparison
- Bar Chart for Top Products and Categories
- Donut Chart for Customer Segment Distribution
- Filled Map for Regional and State-wise Sales
- Matrix/Table for Detailed Sales Records
- KPI Cards for Business Summary
- Slicers for Year, Month, Region and Category Filtering

# Top 5 KPI Used

### Total Sales

Measures the total revenue generated across all completed sales transactions.

### Total Profit

Represents the overall profit earned after accounting for discounts and costs.

### Total Orders

Displays the total number of unique products or customer orders processed during the selected period.

### Return Rate

Measures the percentage of products returned by customers, helping evaluate customer satisfaction and product quality.

### Profit Margin

Calculates the percentage of profit generated from total sales, indicating overall business profitability.

# Key Insights

- Identifies the highest revenue-generating products and categories.
- Tracks monthly sales growth and future sales forecasts.
- Highlights products contributing to business losses.
- Evaluates regional sales performance and customer distribution.
- Measures return rates and their impact on profitability.
- Supports strategic pricing, inventory planning, and business growth.

# Dataset

### Source

**Superstore Sales Dataset**

**Dataset Link:**

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final


# Dashboard Preview

![Buisness Sales Analytics Dashboard](https://github.com/Dhruv250311-hash/Buisness-Sales-Anaytics-Dashboard/blob/main/Sales_Analytics.png)

# Key Performance Analytics

![Buisness Sales Analytics Dashboard](https://github.com/Dhruv250311-hash/Buisness-Sales-Anaytics-Dashboard/blob/main/Key_Performance_Analytics.jpeg)

# 30 Days - Sales Forecast 

![Buisness Sales Analytics Dashboard](https://github.com/Dhruv250311-hash/Buisness-Sales-Anaytics-Dashboard/blob/main/Sales_Forecast_30.jpeg)



This project is intended for educational and portfolio purposes only.

© 2026 Dhrubajyoti Das. All Rights Reserved.
