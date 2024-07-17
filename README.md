PIZZA SALES PROJECT WITH SQL & POWERBI

🍕PIZZA SALES PROJECT

OVERVIEW

The Pizza Sales Report project is designed to provide insights into the sales performance of a pizza restaurant.  SQL for data extraction and data management and Power BI for data visualization, 
this project aims to deliver comprehensive analytics on sales trends, customer preferences and to improve sales .

📁 Dataset Overview

The Dataset includes information on, 

Pizza ID,
Order ID,
Pizza Name,
Order Date,
Order Time,
Unit Price,
Total Price,
Pizza Size,
Pizza Category,
Pizza Ingredients.

Problem Statement

KPI's:

Analyzed key indicators for pizza sales data to gain insights into business performance, calculate the following metrics using SQL and Powerbi
and visualized key insights using charts.

1. Total Revenue:
 
2. Average Order Value:
 
3. Total Pizzas Sold:

4. Total Orders:

5. Average Pizzas Per Order:

6.Daily Trend for Total Orders:

7.Monthly Trend for Total Orders:

8.Percentage of Sales by Pizza Category:

9.Total Pizzas Sold by Pizza Category:

10.Top 5 Best Sellers by Revenue, Total Quantity and Total Orders

11. Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders

###STEPS INVOLVED

- Step 1 : Data Acquisition
The project begins with the acquisition of raw sales data.

- Step 2: Data Transformation with SQL
SQL (Structured Query Language) is used to clean, filter, and transform the raw data into a format suitable for analysis.
This may involve tasks such as joining tables, aggregating data, handling missing values, and creating new calculated fields.

- Step 3. Data Analysis
Once the data is prepared, various SQL queries are written to perform in-depth data analysis for the problem statements.

- Step 4 : Load the dataset to Powerbi. Import SQL file.
- Step 5 : Data Preparation
Calculated required columns using Power Query Calculated KPI requirements using DAX functions.
  1. Total Revenue : The sum of the total price of all pizza orders.
  2.  Total Orders: The total number of orders placed.Distinct Count of Order id
  3. Average Order Value: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
  4. Total Pizzas Sold: The sum of the quantities of all pizzas sold.
  5. Average Pizzas Per Order: The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.
- Step 6 : In the report view, under the view tab, selected visuals and charts as per the requirement
   1. Page - 1:  Key Insights and Trends
   2. Page - 2:  Top 5 and Bottom 5 Performers  
- Step 7 : Slicer: Filter insights based on specific Pizza Category.
- Step 8 : Date Picker: Filter insights based on specific date ranges.
- Step 9 : Navigator Buttons: Seamlessly navigate between the two report pages.
- Step 10 : Add key insights as per the report.
           

  # PAGE 1 : KEY INSIGHTS AND TRENDS:

  This page highlights the overall performance and daily trends in pizza sales using various visualizations:

-> 📊 Key Performance Indicators (KPIs): Display key observations and insights.

-> 📊 Stacked Column Chart: Created a bar chart that displays the daily trend of total orders over a specific time period.
         This chart will help us identify any patterns or fluctuations in order volumes on a daily  Show daily trends in total orders.

-> 📈 Area line Chart: Created a line chart that illustrates the monthly trend of total orders 

-> 🍩 Donut Chart: Created a Donut chart that shows the distribution of sales across different pizza categories.
         This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.
  
-> 🍩 Donut Chart:Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. 
           This chart will help us understand customer preferences for pizza sizes and their impact on sales.

  SCREENSHOT : 

-> 📉 Funnel Chart: Display the total pizzas sold by pizza category.

 # PAGE 2 : TOP 5 AND BOTTOM 5 PERFORMERS

 This page focuses on identifying the top 5 and bottom 5 performing pizzas:

-> 📊 Stacked Bar Chart: Top 5 pizzas by revenue.

-> 📊 Stacked Bar Chart: Top 5 pizzas by quantity.

-> 📊 Stacked Bar Chart: Top 5 pizzas by total orders.

-> 📊 Stacked Bar Chart: Bottom 5 pizzas by revenue.

-> 📊 Stacked Bar Chart: Bottom 5 pizzas by quantity.

-> 📊 Stacked Bar Chart: Bottom 5 pizzas by total orders.

  SCREENSHOT : 


# 🔄 Interactive Features

To enhance the user experience and provide deeper insights, the report includes:

📅 Date Picker: Filter insights based on specific date ranges.

🔘 Slicer: Select and filter data by pizza categories.

🔄 Navigator Buttons: Seamlessly navigate between the two report pages.

# 🔍 Conclusion
This Power BI dashboard provides a detailed analysis of pizza sales, helping to identify trends on basis of days and months , Sales performance 
and top 5 and bottom 5 performing pizzas, based on Revenue, Quantity, Total Orders ,which can be invaluable for business decision-making to improve the sales.




