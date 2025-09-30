🛒 Sales Analysis with Pandas

This repository contains a complete data analysis project on sales data using Python (Pandas, NumPy, Matplotlib). The goal is to answer real-world business questions through data cleaning, transformation, aggregation, and visualization.

📘 Project Overview

The notebook demonstrates the end-to-end process of analyzing sales transactions to uncover patterns, trends, and insights that can help businesses make data-driven decisions.

The analysis includes:

Importing and merging multiple monthly sales files into a single dataset

Data cleaning (handling NaN values, removing duplicates, correcting data types)

Creating new calculated columns for better analysis (e.g., Month, Sales, City)

Answering key business questions using Pandas

Visualizing results with Matplotlib charts

🔎 Questions Solved in This Project

✔️ What was the best month for sales?

Used groupby('Month') and aggregated total sales.

Visualized with a bar chart.

✔️ Which city had the highest number of sales?

Extracted city information from the "Purchase Address" column.

Used groupby('City') to find city-wise totals.

Visualized with a bar chart for comparison.

✔️ What time should advertisements be displayed to maximize sales?

Converted Order Date column into datetime format.

Extracted the hour and plotted sales by hour.

Used a line chart to show peak order hours.

✔️ What product sold the most and why?

Counted occurrences of each product using groupby('Product').

Checked correlation with price using scatterplots.

Visualized with a bar chart of top-selling products.

✔️ What products are most often sold together?

Used duplicated() and grouping on Order ID to find products sold in the same transaction.

Created combination analysis to identify pairs like iPhone + Lightning Cable.

📊 Charts & Visualizations

1. Sales by City

Chart: Bar chart (City vs Sales)

Insight: San Francisco generated the most sales, followed by Los Angeles and New York City.
<img width="640" height="480" alt="City Wise Total Sales($)" src="https://github.com/user-attachments/assets/22dc95ae-f333-4a09-93ff-9792f46553fc" />


2. Number of Orders by Hour

Chart: Line plot (Hour vs Number of Orders)

Insight: Peak hours were around 11 AM and 7 PM, ideal times for running advertisements.
<img width="640" height="480" alt="Number of ordrs each hour-Copy1" src="https://github.com/user-attachments/assets/ea4c411a-4636-4590-b46f-2ac9b8157f23" />

3. Most Sold Products

Chart: Bar chart (Product vs Quantity Ordered)

Insight: AAA Batteries and Lightning Cables were top sellers, often purchased alongside high-ticket items (Phones, Laptops).
<img width="640" height="480" alt="Quantity of Products Ordered" src="https://github.com/user-attachments/assets/fa0d3c12-1132-413c-91b4-186183f410b2" />

4. Price vs Quantity Ordered

Chart: Scatter plot (Price vs Quantity Ordered)

Insight: Cheaper products had higher order quantities, while expensive ones (MacBook Pro, iPhones) sold less frequently but contributed more to revenue.
<img width="640" height="480" alt="Quantity of Products Ordered and thei price" src="https://github.com/user-attachments/assets/b750499e-9001-43a7-ad0d-a35acb76a49e" />


🛠️ Tools & Libraries Used

Python 3

Pandas → Data cleaning, grouping, and analysis

NumPy → Numerical operations

Matplotlib → Data visualization (bar, line, scatter plots)

Jupyter Notebook → Running analysis step by step

