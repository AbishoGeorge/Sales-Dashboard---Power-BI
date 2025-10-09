# Sales Dashboard – Power BI Project

An interactive Power BI dashboard analyzing SuperStore sales data across regions, segments, and categories. It highlights key metrics like orders, sales, profit, and shipping trends, helping stakeholders uncover insights, track performance, and make data-driven business decisions.

## Dataset used

[Download Dataset](https://github.com/AbishoGeorge/Sales-Dashboard---Power-BI/blob/main/SuperStore%20Sales%20DataSet.xlsx)

## Business Problem (KPI)

Sales & Profit Performance

 •	What is the total sales, profit, and number of orders?
 •	How has sales and profit trended month-over-month?
 •	Are there specific months or seasons where sales spike?

Customer Segments

 •	Which customer segment (Consumer, Corporate, Home Office) brings in the most revenue?
 •	Are certain segments more profitable than others?

Regional Insights

 •	Which regions or states are generating the highest sales?
 •	Are there underperforming regions that need attention?

Product Analysis

 •	What are the top-performing product categories and sub-categories?
 •	Are there specific products or categories that are not profitable?

Shipping & Logistics

 •	What is the average shipping time?
 •	Which shipping mode is used most frequently, and how does it impact profit?

Payment Behavior

 •	What are the most commonly used payment methods?
 •	Is there a preference for COD, Online, or Card payments?

## Goal of the Dashboard

 •	Track and visualize key metrics: Orders, Sales, Profit, Shipping Days
 •	Break down data across Region, Segment, Payment Mode, Ship Mode, and Time
 •	Make it easy to spot trends, compare categories, and identify areas that need attention
 •	The goal was to create a command center-style dashboard that gives users instant visibility into performance.

## Process

 •	The process began by exploring the SuperStore dataset to understand the structure, key fields, and potential insights.
 •	Next, the data was cleaned and prepped in Power BI — correcting data types, handling missing values, and standardizing formats.
 •	Relationships between tables were then created to build a proper data model that supports accurate filtering and aggregation.
 •	Visuals were designed using appropriate chart types, with a clear layout and interactive slicers to enhance usability.
 •	Finally, insights were analyzed, and the dashboard was refined with labels, tooltips, and formatting to ensure clarity and professionalism.

## Dashboard Overview

The project includes two main pages:

Page 1: Performance Summary (Sales, Profit, Region, Segment, etc.)

Page 2: 30-Day Sales Forecast with Time-Series Trends

<img width="1324" height="739" alt="Screenshot 2025-10-09 073832" src="https://github.com/user-attachments/assets/0fb2f623-89fc-4296-9ec9-a932af9c196f" />

<img width="1320" height="742" alt="Screenshot 2025-10-09 073310" src="https://github.com/user-attachments/assets/b13d4d73-ab94-424c-8d0e-97092e110d88" />

## Visual Walkthrough (Some Highlights)

Here are a few of the visuals I’d like to point out:

 i. Sales by Payment Mode:
This donut chart shows the split across Cash on Delivery (COD), Online, and Card payments. COD accounts for 43% of total sales, which surprised me. This could have implications on risk, logistics, and customer behavior.

 ii. Sales by Region:
I used another donut chart here to break down sales geographically. The West region clearly leads with 33% of sales, while the South is lagging at just 16%. This kind of insight helps in planning region-specific marketing campaigns.

 iii. Sales & Profit by Month:
This one’s a line chart showing seasonality. There’s a clear spike in sales and profit in November and December, pointing to holiday season demand. Super useful for inventory planning and forecasting.

 iv. Sales Forecast Line Chart:
A detailed time series chart with historical daily sales (from 2019–2021) and a 30-day forecast visualized in green. This helps in short-term planning based on predictive trends.

 v. Zoomed Forecast View:
The bottom chart focuses on the most recent months to give a closer look at how sales have behaved before and how they’re expected to trend. It’s useful for monitoring recent spikes and dips.

## Key Insights

 •	Sales have shown consistent growth, with clear peaks in November and December — likely due to holiday demand.
 •	The 30-day forecast indicates continued upward trends, helping teams prepare ahead for inventory and marketing.
 •	California, New York, and Texas are the top-performing states in terms of sales volume.
 •	COD is the most popular payment method (43%), which has implications for operations and cash flow.
 •	The Consumer segment (48%) is the biggest revenue driver — an important focus for marketing.
 •	Standard Class shipping dominates in usage, but First Class brings in higher margins, suggesting room for optimization

## Business Impact

 •	If this dashboard were in use by a real company like SuperStore, here’s how it could help:
 •	Sales teams can focus efforts on high-performing regions and product lines.
 •	Ops teams can optimize shipping methods based on cost and customer preference.
 •	Marketing can target key customer segments more effectively.
 •	Finance can monitor profit trends and plan more accurately for peak seasons.

## Data Columns Used

Here’s the dataset structure that powered this dashboard:

Row ID, Order ID, Order Date, Ship Date, Ship Mode
Customer ID, Customer Name, Segment, Country, City, State, Region
Product ID, Category, Sub-Category, Product Name
Sales, Quantity, Profit, Returns, Payment Mode

## Tools Used

 •	Excel – for initial data cleaning and loading
 •	Power BI – for building the dashboard and visuals

## Conclusion

This Power BI project demonstrates how raw sales data can be transformed into a meaningful, interactive dashboard that supports real business decisions. By combining performance analysis with short-term forecasting, the dashboard provides a complete picture — from understanding what has happened to preparing for what’s next.
Whether it's identifying top-performing regions, spotting seasonal trends, or forecasting future demand, the insights gathered here can directly support sales, operations, and marketing strategies.
The goal was not just to visualize data, but to create a tool that delivers actionable insights — something business users can rely on to make informed decisions, faster.

Thanks for Visiting!

⭐ If you found this useful, feel free to star the repo!
