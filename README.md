# Sales Dashboard – Power BI Project

An interactive Power BI dashboard analyzing SuperStore sales data across regions, segments, and categories. It highlights key metrics like orders, sales, profit, and shipping trends, helping stakeholders uncover insights, track performance, and make data-driven business decisions.

## Dataset used

<a href="https://github.com/AbishoGeorge/Sales-Dashboard---Power-BI/blob/main/SuperStore%20Sales%20DataSet.xlsx"><Sales Dataset/a>

## 1. Business Problem (KPI)

### Sales & Profit Performance

•	What is the total sales, profit, and number of orders?

•	How has sales and profit trended month-over-month?

•	Are there specific months or seasons where sales spike?

### Customer Segments

•	Which customer segment (Consumer, Corporate, Home Office) brings in the most revenue?

•	Are certain segments more profitable than others?

### Regional Insights

•	Which regions or states are generating the highest sales?

•	Are there underperforming regions that need attention?

### Product Analysis

•	What are the top-performing product categories and sub-categories?

•	Are there specific products or categories that are not profitable?

### Shipping & Logistics

•	What is the average shipping time?

•	Which shipping mode is used most frequently, and how does it impact profit?

### Payment Behavior

•	What are the most commonly used payment methods?

•	Is there a preference for COD, Online, or Card payments?

## 2. Goal of the Dashboard

My main goal here was to build an interactive and easy-to-understand dashboard using Power BI that could:

•	Track and visualize key metrics: Orders, Sales, Profit, Shipping Days

•	Break down data across Region, Segment, Payment Mode, Ship Mode, and Time

•	Make it easy to spot trends, compare categories, and identify areas that need attention

•	I wanted this dashboard to act like a command center for business users — something they could glance at and immediately get a sense of what’s happening.

## Process

•	The process began by exploring the SuperStore dataset to understand the structure, key fields, and potential insights.

•	Next, the data was cleaned and prepped in Power BI — correcting data types, handling missing values, and standardizing formats.

•	Relationships between tables were then created to build a proper data model that supports accurate filtering and aggregation.

•	Visuals were designed using appropriate chart types, with a clear layout and interactive slicers to enhance usability.

•	Finally, insights were analyzed, and the dashboard was refined with labels, tooltips, and formatting to ensure clarity and professionalism.

## Dashboard



## 3. Visual Walkthrough (Some Highlights)

Here are a few of the visuals I’d like to point out:

### Sales by Payment Mode

This donut chart shows the split across Cash on Delivery (COD), Online, and Card payments. COD accounts for 43% of total sales, which surprised me. This could have implications on risk, logistics, and customer behavior.

### Sales by Region

I used another donut chart here to break down sales geographically. The West region clearly leads with 33% of sales, while the South is lagging at just 16%. This kind of insight helps in planning region-specific marketing campaigns.

### Sales & Profit by Month

This one’s a line chart showing seasonality. There’s a clear spike in sales and profit in November and December, pointing to holiday season demand. Super useful for inventory planning and forecasting.

## 4. Key Insights

•	Consumer Segment makes up nearly half (48%) of all sales – a key audience.

•	Phones are the top-selling sub-category, but Chairs and Binders aren’t far behind.

•	Standard Class shipping brings in the most revenue, but First Class shipping is a high-margin area.

•	Sales in the West are outperforming other regions by a significant margin.

## 5. Business Impact

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

Thanks for Visiting!

If you’ve made it this far, thanks a lot for checking out my project! If you have any feedback, questions, or just want to connect — feel free to reach out.

⭐ If you found this useful, feel free to star the repo!
