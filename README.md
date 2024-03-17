## 🍕PIZZA  SALES ANALYSIS ON MICROSOFT EXCEL/MySQL

 <img align="right" alt="Pizza"   width="350" src="https://user-images.githubusercontent.com/72607039/148701706-7638bdb7-83de-444d-bbcd-8780660f77da.gif">

## Overview:-
I developed a comprehensive Microsoft Excel dashboard for analyzing pizza sales 
data, leveraging Microsoft SQL Server and Power queries. 
This project aimed to provide actionable insights for optimizing sales strategies and improving overall business performance.

## Problem Statement:-
### 🎯KPIs Requirement: 
Client: We need to analyze the key indicators for our Pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:
1. Total Revenue
2. Average Order Value
3. Total Pizzas Sold
4. Total Orders
5. Average Pizzas Per Order

### 📊Charts Requirements:- 
Client: We would like to visualize various aspects of our Pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts:
1. Daily Trend for Total Orders: A Bar chart to display the daily trend of total orders over a specific time period. This chart will help us to identify any patterns or fluctuations in order volumes on a daily basis.
2. Hourly Trend for Total Orders: A Line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high-order activity.
3. Percentage of Sales by Pizza Category: A Pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.
4. Percentage of Sales by Pizza Size:  A Pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.
5. Total Pizzas Sold by Pizza Category: A Funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.
6. Top 5 Best Sellers by Total Pizza Sold: A Bar chart highlighting the Top 5 Best Selling Pizzas based on the total number of Pizzas Sold. This chart will help us identify the most popular pizza options.
7. Bottom 5 Worst Sellers: A Bar chart showcasing the Bottom 5 Worst Selling Pizzas based on the Total Number of Pizzas Sold. This chart will enable us to identify underperforming or less popular pizza options.

## Data Cleaning and Transformation::-
Employed SQL queries for data cleaning and transformation, ensuring data accuracy and reliability. Addressed any inconsistencies in the raw data to enhance the overall quality.

## Analysis:-

Analysis was done on SQL and visualized on Microsoft Excel. I chose to use SQL for the analysis because With SQL, you can analyze small and big datasets, investigate problems and generate sales reports faster. 
I uploaded the dataset first on SQL Server where I did all the analysis before visualizing it on Microsoft Excel.

### Findings:-

Year considered - 2015

Total_Orders - 21,350	

Number_of_pizza_types - 32	

Total_Quantity_Sold	- 49,574

Total_revenue - $817,860.05	

Average_revenue - $16.82

1. The busiest time of the day is between 12pm and 1pm which is Lunch period. For 12pm, a total of 2,520 orders was received, 6,776 quantites of Pizzas were made and revenue generated was $111,877.9 while for 1pm, a total of 2,455 orders was received, 6,413 quantities of Pizza made and revenue generated was $106,065.7.

    ![Screenshot 2024-01-08 085813](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/7f6f5f1e-74bb-4349-9340-95bbc13b4714)

2. The busiest days are Fridays and Saturdays (Beginning of the weekend). With Fridays having a total of 3,538 orders, 8,242 quantities of pizzas made, and revenue generation of $136,073.9. While on Saturdays, orders received was 3,158, with a total of 7,493 pizzas made and revenue generation of $123,182.4.

    ![Screenshot 2024-01-09 092303](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/3c337139-2025-4f0f-8ad5-dc3ed8cd3557)

3. Our overall best selling pizza is The Classic Deluxe Pizza. It was ordered 2,416 times, a total of 2,453 quanties was sold and it generated revenue of $38,180.5. The worst selling pizza is The Brie Carre Pizza	with a total of just 480 orders, 490 quantities made and revenue of	$11,588.5.

    ![Screenshot 2024-01-09 092716](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/4f04736d-d97d-49f3-a282-7911d279926b)

 4. The highest sold pizza size is the Large Size with a total of 8,123 orders placed for it,	18,956 quantites sold and revenue generation of $375,318.7, the least sold pizza size is the XXL with just 14 orders, 28 quantities sold and $1,006.6 revenue generated.
  
     ![Screenshot 2024-01-09 093329](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/d5f582ab-8af3-4000-89cb-4ae44f6cf60f)

5. The pizza category which is most in demand is the Classic	with 6,438 orders placed for it, 14,888 quantities sold and	$22,0053.1 revenue generated.  

     ![Screenshot 2024-01-09 093823](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/e3a4c5d1-92a2-46c6-9b06-eaf3f13a7a89)


# Visualization:-
![Screenshot 2024-01-08 085036](https://github.com/GoutamKuiri99/Pizza_sales_Dashboard_Excel_Project/assets/154737280/279be72c-693e-4525-b056-a9aaafe0e8d3)

# Conclusion:-
Pizza orders and revenue maintains an upward trajectory from the beginning of the week Sunday and peaks on Friday before it starts dropping, this means most people prefer to eat pizza towards and during the weekend. Most people prefer to have the Pepperoni pizza for lunch on Fridays. It is advisable to make available tables and chairs to be able to accomodate the influx of the weekend, we can also explore the option of delivery services. The Ingrdients for  Pepperoni pizza should be made readily available and in large quantities on or before Fridays. Since more orders are received on Fridays, a discount policy can be introduced every last Friday of the month where a customer gets 1 extra pizza when they buy 3 and above, this will encourage them to buy more. 

















