# 🍕 Pizza Sales Report

An interactive Power BI dashboard built on top of a SQL-cleaned dataset to explore a full year of pizza sales—covering revenue trends, order patterns, category performance, and best/worst selling products.

## Short Description / Purpose

The Pizza Sales Report is a Power BI dashboard, backed by SQL for data extraction and analysis, that helps track and understand a pizzeria's sales performance across 2015. It highlights revenue trends, ordering behavior, category and size performance, and identifies top and bottom performing products—giving a clear picture of what's driving (or dragging) the business.

## Tech Stack

The dashboard was built using the following tools and technologies:

- 🗄️ **SQL** – Used to query, clean, and aggregate the raw sales data (orders, order details, pizzas, pizza types) before analysis.
- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data within Power BI.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures like Total Revenue, Avg Order Value, and Avg Pizzas per Order, as well as ranking logic for best/worst sellers.
- 📁 **File Format** – `.pbix` for development, `.docx` file for SQL Queries with their results and `.png` for dashboard previews.

## Features / Highlights

### Business Problem
The stakeholder needed a way to analyze key indicators from raw pizza sales data to understand overall business performance — sales volume, ordering patterns, and which products were driving (or dragging) revenue.

### Requirements

**KPI Requirements** — the following metrics needed to be calculated:
1. **Total Revenue** – The sum of the total price of all pizza orders.
2. **Average Order Value** – Total revenue divided by the total number of orders.
3. **Total Pizzas Sold** – The sum of the quantities of all pizzas sold.
4. **Total Orders** – The total number of orders placed.
5. **Average Pizzas Per Order** – Total pizzas sold divided by total orders.

**Chart Requirements** — the following visuals were requested to surface trends:
1. **Daily Trend for Total Orders** – Bar chart of total orders by day, to spot daily patterns.
2. **Monthly Trend for Total Orders** – Line chart of order volume by month, to spot peak periods.
3. **Percentage of Sales by Pizza Category** – Pie/donut chart of sales distribution across categories.
4. **Percentage of Sales by Pizza Size** – Pie/donut chart of sales share by pizza size.
5. **Total Pizzas Sold by Pizza Category** – Chart comparing sales performance across categories.
6. **Top 5 Best Sellers by Revenue, Quantity, and Total Orders** – To identify the most popular pizzas.
7. **Bottom 5 Worst Sellers by Revenue, Quantity, and Total Orders** – To flag underperforming pizzas.

### Goal of the Dashboard
To deliver an interactive reporting tool that:
- Summarizes overall sales performance through key KPIs.
- Identifies best-selling and worst-selling pizzas by revenue, quantity, and orders.
- Reveals ordering trends by day, month, category, and size.
- Supports data-driven decisions on menu planning, staffing, and promotions.

### Walkthrough of Key Visuals

**Page 1 – Home**
- **Key KPIs (Top Row):** Total Revenue (817.86K), Avg Order Value (38.31), Total Pizzas Sold (49,574), Total Orders (21,350), Avg Pizzas per Order (2.32).
- **Busiest Days & Times:** Orders are highest on weekend evenings, particularly Friday and Saturday, shown via a daily trend bar chart.
- **Monthly Trend:** A line chart of total orders by month shows July and January as the peak months.
- **% of Sales by Pizza Category:** Donut chart breaking down sales share across Classic, Supreme, Veggie, and Chicken categories—Classic leads in contribution.
- **% of Sales by Pizza Size:** Donut chart showing size-wise sales split, with Large size driving the highest sales.
- **Total Pizzas Sold by Pizza Category:** Bar chart ranking categories by total units sold.

**Page 2 – Best/Worst Sellers**
- **Top 5 Pizzas by Revenue, Quantity, and Total Orders:** The Thai Chicken Pizza leads in revenue, while the Classic Deluxe Pizza tops both quantity sold and total orders.
- **Bottom 5 Pizzas by Revenue, Quantity, and Total Orders:** The Brie Carre Pizza consistently ranks lowest across all three metrics.
- **Continent-style filter panel equivalent:** A Pizza Category slicer and date range slider at the top let users filter every visual by category and time period.

### Business Impact & Insights
- **Menu Optimization:** Management can double down on high performers like the Thai Chicken and Classic Deluxe pizzas while reassessing low performers like the Brie Carre Pizza.
- **Staffing & Operations:** Knowing that Friday/Saturday evenings and the months of July and January are peak periods helps with staffing and inventory planning.
- **Promotional Strategy:** Size and category breakdowns (Large size and Classic category leading sales) can guide targeted promotions and combo offers.
- **Revenue Tracking:** A single view of Total Revenue, Avg Order Value, and Avg Pizzas per Order gives a quick pulse check on overall business health.

## Screenshot

**Home Page**
![Home Page](https://github.com/shivam-0919/Pizza_Sales_Report/blob/main/Home.png)


**Best/Worst Sellers**
![Best/Worst Sellers](https://github.com/shivam-0919/Pizza_Sales_Report/blob/main/Best-Worst%20Sellers.png)


