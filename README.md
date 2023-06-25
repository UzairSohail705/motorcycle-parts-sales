## Overview
The company sells motorcycle parts to both wholesale and retail customers, with 3 operating warehouses. They offer a variety of parts and offer payment through card, cash and bank transfer. The analysis seeks to gain a better understanding of wholesale revenue by product line, and how this varies month-to-month and across warehouses. 

There is one table:

![1](https://github.com/UzairSohail705/motorcycle-parts-sales/assets/137323836/0a4cbe24-13f1-42ce-b56c-58ba29cbd31d)

## Analysis

The first part of code aggregates sales data by product line, month, warehouse, payment fee, and client type. It then calculates the net revenue for wholesale clients by subtracting the payment fee from the total sales. The final result set presents the product line, month, warehouse, and net revenue, filtered for wholesale clients, and sorted by product line, month, and net revenue in descending order.

Here are the results:

![2](https://github.com/UzairSohail705/motorcycle-parts-sales/assets/137323836/50e48229-4f74-48bc-8a47-d56ea941f3fe)

The second part of code retrieves metrics such as the total number of orders, the percentage of retail and wholesale orders, the total quantity of products sold, the total revenue, and the average order value for each warehouse. The result set is grouped by the warehouse column, providing insights into the performance and characteristics of different warehouses based on sales data.

Here are the results:

![3](https://github.com/UzairSohail705/motorcycle-parts-sales/assets/137323836/d8ba150a-07a9-40e3-bebf-c1c2f24d0fab)

## Insights

* Central region is the most beneficial warehouse in terms of bottomline.
* West region lags behind the other two regions in every key number.
* The average order value of West region is significantly lower than the others, which needs to be investigated.
  
