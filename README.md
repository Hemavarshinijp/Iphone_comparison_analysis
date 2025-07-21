# Iphone_comparison_analysis

# 📊 iPhone Sales Variance Dashboard

This Power BI project analyzes and compares **iPhone 14** and **iPhone 15** sales data across countries. It highlights total sales, absolute differences, and percentage variances to understand market trends.

---

## 📁 Datasets Used

- `fact_sales_Iphone14.csv` – Sales data for iPhone 14
- `fact_sales_Iphone15.csv` – Sales data for iPhone 15
- `dim_stores.csv` – Store and country metadata

---

## 🔧 Key Steps Performed

--> Review the data (fact_sales_Iphone14 and fact_sales_Iphone15). 
--> Metrics to compare - iPhone 14 sales and iPhone 15 sales. 
# Iphone14_Sales = SUM(fact_sales_Iphone14[iphone14])
# Iphone15_Sales = SUM(fact_sales_Iphone15[iphone15])
--> Calculate the variance (absolute difference value) between the iPhone 15 sales 
and iPhone 14 sales for the identified metrics. 
# ABS([Iphone 15 Sales]-[Iphone 14 Sales]). 
--> Calculate the variance (in percentage) between the iPhone 15 sales and iPhone 
14 sales for the identified metrics. 
# [([Iphone 15 Sales]-[Iphone 14 Sales])/[Iphone 14 Sales]. 
--> Provide a complete report of the difference in numbers between the iPhone 15 
sales and iPhone 14 sales data across the top 10 countries. 

## Data Visualization

iPhone14 Sales Card – Shows total iPhone14 sales (1232K).

iPhone15 Sales Card – Shows total iPhone15 sales (1180K).

Absolute Variance Card – Displays the difference in sales (53K).

Sales Variance % Card – Shows the percentage change in sales (-4.26%).

Table Visual – Compares country-wise iPhone14 & 15 sales with variance and icons.

Bar Chart (Top Right) – Shows Absolute Variance by country.

Bar Chart (Bottom Right) – Displays Sales Variance % by country.

Stacked Bar Chart (Bottom Center) – Compares iPhone14 vs iPhone15 sales by country.
