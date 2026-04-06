# Sales-Performance
Project Overview

The Sales Performance Analysis Dashboard is a Power BI business intelligence project designed to analyze sales data and generate meaningful insights for business decision-making.

This dashboard helps stakeholders evaluate sales performance, monitor profitability, identify top-performing regions and products, and understand customer purchasing behavior through interactive visualizations and KPI tracking.

Objective of the Project

The main objective of this project is to analyze business sales performance and answer important business questions such as:

How much revenue is being generated?
Which regions and product categories contribute the most?
Which products drive maximum profit?
Are there seasonal trends in sales?
Who are the top customers?

This dashboard supports data-driven decision-making for sales strategy, inventory planning, and profitability improvement.

 Tools & Technologies Used
Power BI – Dashboard development and visualization
Power Query – Data cleaning and transformation
DAX (Data Analysis Expressions) – KPI and measure creation
CSV / Excel Dataset – Source data

Dataset Description

The dataset used in this project contains sales transaction details with the following fields:

Order ID – Unique identifier for each order
Order Date – Date of purchase
Customer Name – Customer who placed the order
Product – Item sold
Category – Product category
Quantity – Units purchased
Unit Price – Selling price per unit
Cost Price – Cost per unit
Region – Sales region
Sales – Total revenue generated
Profit – Profit earned from sales
Project Workflow / Methodology
Step 1 – Data Loading

The sales dataset was imported into Power BI using:

Get Data → Text/CSV

Step 2 – Data Cleaning (Power Query)

The dataset was cleaned and transformed using Power Query.

Tasks Performed:
Converted data types
Parsed date fields
Created new columns:
Year
Month
Step 3 – DAX Measures Created

The following key DAX measures were created for analysis:

Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Quantity Sold = SUM(Sales[Quantity])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0) * 100
Step 4 – Visualization Building

Several interactive visuals were created in Power BI to analyze business performance.

Visuals Used:
Bar Charts
Donut Charts
Line Graphs
KPI Cards
Tables / Summary Visuals
Business Questions Answered

This dashboard was built to answer the following analytical questions:

Q1. What is the overall total sales, total profit, and profit margin?

To understand overall company performance at a high level.

Q2. How are sales and profit distributed across different regions?

To identify the strongest and weakest performing markets.

Q3. Which product categories contribute the most to revenue?

To guide business investment and stock planning decisions.

Q4. What are the monthly sales trends throughout the year?

To detect seasonality and peak sales periods.

Q5. Which products generate the highest revenue?

To optimize product strategy and focus on best-selling items.

Q6. Who are the top customers based on spending?

To identify premium customers for retention and loyalty strategies.

Key Performance Indicators (KPIs)

The dashboard tracks the following KPIs:

Total Sales
Total Profit
Total Quantity Sold
Profit Margin %
Monthly Sales Trend
Regional Sales Performance
Top Products
Top Customers
Insights & Findings

Some of the major insights identified from the dashboard include:

Certain regions outperform others, contributing significantly to total revenue.
Categories such as Electronics show high sales volume and strong profit margins.
Seasonal sales patterns are visible, with some months showing higher sales spikes.
A small group of customers contributes a large share of total sales.
Profitability varies across products, highlighting areas for business improvement.
Conclusion

The Sales Performance Analysis Dashboard successfully provides valuable business insights and helps management understand:

Which regions are performing well
Which products should be promoted or stocked
Who the most loyal and high-value customers are
How profit trends correlate with sales
Which months generate the highest revenue

This dashboard can support decision-making in:

Sales Strategy
Marketing Planning
Inventory Management
Pricing Decisions
Business Growth Monitoring
