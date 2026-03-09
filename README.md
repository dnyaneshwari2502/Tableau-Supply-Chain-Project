# Supply Chain Performance Dashboard (Tableau)

## Project Overview
This project focuses on analyzing the supply chain and sales performance using Tableau. The goal was to explore how sales, profitability, and shipping efficiency vary across regions, product categories, and shipping modes. The dashboard brings together key operational metrics that help answer common business questions related to demand patterns, logistics efficiency, and product profitability.

The analysis uses the Global Superstore dataset and presents insights through an interactive Tableau dashboard.

## Purpose of the Project
The main objective of this project was twofold:

1. To perform a structured supply chain analysis using real-world style data.
2. To deepen my hands-on experience with Tableau by building a complete analytics dashboard from scratch.

While I have previously worked with business intelligence tools in industry projects, this project was part of my personal upskilling effort to strengthen my Tableau expertise and understand how to design clean, interactive dashboards for business decision-making. I wanted to gain deeper hands-on experience with Tableau since I had not previously worked with it extensively in industry-based projects.

## Business Questions Addressed
The dashboard helps answer several important questions:

- Which regions or countries generate the highest sales?
- Which product categories contribute the most profit?
- How do sales vary over time?
- Which shipping modes handle the most orders?
- How long does it take for orders to ship after they are placed?
- Which product sub-categories generate high sales but low profit?

These insights help organizations better understand demand patterns and identify potential operational improvements.

## Dataset
The project uses the **Global Superstore dataset**, which includes:

- Order Date
- Ship Date
- Shipping Mode
- Region, Country, City
- Product Category and Sub-Category
- Sales
- Profit
- Quantity
- Customer Segment

This dataset allows analysis of both **sales performance and supply chain behavior**.

## Key Metrics Used
Several key metrics were used in the dashboard:

- Total Sales
- Total Profit
- Total Orders
- Average Shipping Days
- Sales Trend Over Time
- Profit by Product Category
- Sales by Shipping Mode
- Shipping Time Distribution

A calculated field was created to analyze logistics performance:

**Shipping Days = DATEDIFF('day', [Order Date], [Ship Date])**

This metric helps understand order fulfillment time.

## Dashboard Components
The Tableau dashboard includes the following visualizations:

1. **KPI Summary Cards**
   - Total Sales
   - Total Profit
   - Total Orders
   - Average Shipping Days

2. **Monthly Sales Trend**
   A time-series view showing how sales evolved across months.

3. **Sales by Country (Map Visualization)**
   Highlights geographic demand and helps identify strong markets.

4. **Profit by Product Category**
   Shows which product categories drive profitability.

5. **Sales by Shipping Mode**
   Compares performance across different shipping methods.

6. **Shipping Time Distribution (Days)**
   A histogram showing how long orders typically take to ship.

7. **Sales vs Profit by Sub-Category**
   A scatter plot is used to analyze the relationship between sales and profit across product sub-categories. Reference lines are used to highlight performance quadrants and identify high- and low-performing product segments.

The dashboard also supports interactive filtering by selecting regions directly on the map.

## Tools Used
- Tableau Public
- Excel (Global Superstore dataset)

## Key Learning Outcomes
Through this project, I strengthened my understanding of:

- Tableau dashboard design
- Interactive analytics
- Visual storytelling with data
- Supply chain performance analysis
- Creating calculated fields and custom metrics
- Designing dashboards with a clear analytical flow
- Building multi-chart dashboards that support business decision making

## How to View the Dashboard
You can download the Tableau workbook from this repository and open it using **Tableau Public**.

## Repository Contents
dataset/  
Global-Superstore.xlsx  

dashboard/  
SupplyChain_Performance_Dashboard.twbx  

Output/  
Dashboard_Screenshot.png  

## Author
**Dnyaneshwari Rakshe**  
MS Data Science — University of Colorado Boulder

This project is part of my continuous effort to build strong practical skills in data analytics, business intelligence, and applied data science.

**Thank You!**
