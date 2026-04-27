# Coffee Sales Interactive Dashboard
## Project Objective
To analyse coffee sales data in order to:
1. Identify sales trends over time
2. Understand customer purchasing behaviour
3. Evaluate product performance by roast type and size
4. Support strategic marketing and customer retention
### Dataset
<a href="https://github.com/ShingaiMhene/Coffee-Sales-Dashboard/blob/main/coffeeOrdersData.xlsx">Dataset</a>
## Business Questions
1. How do coffee sales trends change over time?
2. Which roast types (Dark, Medium, Light) perform best?
3. What impact does product size have on sales?
4. Which countries generate the highest revenue?
5. Who are the top 5 customers by total sales?
6. Does having a loyalty card influence purchasing behaviour?

Interactive Dashboard
<a href= "https://github.com/ShingaiMhene/Coffee-Sales-Dashboard/blob/main/Coffee%20Sales%20Dashboard.xlsx"> Download Dashboard</a>
## Process
1. Used XLOOKUP to map and retrieve:
Coffee Type
Roast Type
Unit Price
2. Created a calculated column:
Sales = Quantity × Unit Price
3. Cleaned and standardised data:
4. Removed abbreviations:
Roast types (L, D, M → Light, Dark, Medium)
Coffee types (Rob, Liberica, Excelsa → full names using IF function)
5. Applied formatting:
Standardised date formats for time-series analysis
Formatted product sizes for consistency
6. Created pivot tables and charts for
Total Sales
Sales by Country
Customer Revenue Rankings

### Dashboard
<img width="1281" height="728" alt="Coffee Sales" src="https://github.com/user-attachments/assets/b54722a7-5c0d-4e89-8ef8-2092030b2124" />



## Key Insights
Sales show fluctuations over time, indicating seasonal or demand variability
Arabica and Robusta are among the most frequently purchased coffee types
The United States generates the highest revenue, significantly outperforming other regions
A small group of customers contributes significantly to revenue (top 5 customers)
Product preferences vary by roast type and size, influencing purchasing patterns
## Recommendations
Focus marketing efforts on high-performing regions (e.g., United States)
Develop loyalty programs to retain top customers
Optimise inventory based on popular roast types and sizes
Leverage seasonal trends to plan promotions and campaigns
