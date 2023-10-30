[Bike sales ANALYTICS.pdf](https://github.com/kikibyt/Bike_sales-_report/files/13209758/Bike.sales.ANALYTICS.pdf)

# Bike Sales Report
![output 8](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/7a2cd947-2b12-4058-988c-35ded29fb51d)

![output2](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/67b5adc4-a913-49b4-813c-80d0511fd951)
![output 3](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/790afdbe-2553-4768-ba67-956d7c02ad29)
![output 4](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/7d524f0b-39b3-4cae-894c-b95085dc3587)
![output 6](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/a180b388-b720-47bb-974b-006de7556da5)
![output 7](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/8016cd99-2c37-4c04-a010-5647c1dca516)
![output 5](https://github.com/kikibyt/Bike_sales-_report/assets/127496130/3596e77e-b898-48b3-b43f-fa6a5dc1dd55)

 Data Analysis
BIKE_SALES_ANALYTICS
By MERCY OKEBIORUN
Official report 

"In today's fast-paced and evolving market, understanding the dynamics of bike sales is paramount for both manufacturers and retailers. This bike sales analytics report delves into the data and trends, offering a comprehensive overview of the current state of the industry. By analyzing key metrics and market insights, we aim to provide valuable insights that can guide strategic decisions, enhance sales strategies, and foster growth in this ever-changing landscape."
Title: Unit Cost Distribution Analysis

**Introduction:**
In this section of the analysis, we focus on exploring the distribution of the "Unit Cost" within the dataset. A box plot has been generated to visually represent the spread and characteristics of this particular variable.

**Unit Cost Distribution:**

The box plot illustrates several key insights about the distribution of unit costs:

- The median unit cost is depicted in green, showing a value of $9.00.
- The mean unit cost, denoted in red, is approximately $267.30.

**Box Plot Interpretation:**
The box plot provides valuable information about the unit cost distribution. The following observations can be made:
- The median and mean values are different, indicating potential skewness in the data.
- The box itself represents the interquartile range (IQR), which captures the middle 50% of the unit cost values.
- Outliers are present in the dataset, as indicated by the data points outside the whiskers of the box plot.

**Conclusion:**
The analysis of the unit cost distribution is a crucial step in understanding the financial aspects of the sales data. The presence of outliers suggests that there might be significant variations in unit costs, which could impact the profitability of the products.

This visualization will be useful for further investigation into the factors that affect unit costs and for making informed decisions regarding pricing and cost control.



Title: Analysis of Age Group Distribution and Column Correlation

**Age Group Distribution:**

In the initial part of this analysis, we explore the distribution of sales across different age groups. The bar chart below displays the number of sales in
 each age group. This can provide insights into the customer demographics and their purchasing behavior.



*Insights:*
- The analysis reveals the distribution of sales across different age groups, helping identify which age groups are more active in making purchases.

**Correlation Between Columns:**
In the second part of the analysis, we calculate the correlation matrix among numeric columns in the dataset, including columns like Year, Customer Age, Order Quantity, Unit Cost, Unit Price, Profit, Cost, and Revenue.

*
Correlation Matrix:*

The correlation matrix provides information about how each pair of numeric variables is related. The table below shows the correlation coefficients:

```
                     
Day      Year  Customer_Age  Order_Quantity  Unit_Cost  Unit_Price    Profit      Cost   Revenue
Day             1.000000 -0.007635     -0.014296       -0.002412   0.003133    0.003207  0.004623  0.003329  0.003853
Year           -0.007635  1.000000      0.040994        0.123169  -0.217575   -0.213673 -0.181525 -0.215604 -0.208673
Customer_Age   -0.014296  0.040994      1.000000        0.026887  -0.021374   -0.020262  0.004319 -0.016013 -0.009326
Order_Quantity -0.002412  0.123169      0.026887        1.000000  -0.515835   -0.515925 -0.238863 -0.340382 -0.312895
Unit_Cost       0.003133 -0.217575     -0.021374       -0.515835   1.000000    0.997894  0.741020  0.829869  0.817865
Unit_Price      0.003207 -0.213673     -0.020262       -0.515925   0.997894    1.000000  0.749870  0.826301  0.818522
Profit          0.004623 -0.181525      0.004319       -0.238863   0.741020    0.749870  1.000000  0.902233  0.956572
Cost            0.003329 -0.215604     -0.016013       -0.340382   0.829869    0.826301  0.902233  1.000000  0.988758
Revenue         0.003853 -0.208673     -0.009326       -0.312895   0.817865    0.818522  0.956572  0.988758  1.000000
```

*Insights:*
- The correlation matrix provides information about the relationships between numeric columns.
- For instance, there is a strong negative correlation between Order Quantity and Unit Cost, which could indicate cost savings strategies or pricing policies.
- Understanding these correlations can be essential for making informed decisions in areas such as pricing, cost control, and profitability.

**Conclusion:**
This analysis allows us to gain insights into the age group distribution of sales and the relationships between various numeric columns in the dataset. These insights can be leveraged for making data-driven business decisions.

Title: Data Visualization and Analysis

**Scatter Plot: Revenue vs. Profit**
In this analysis, we start with a scatter plot of Revenue against Profit. The plot provides insights into the relationship between these two crucial financial metrics.



*Insights:*
- The scatter plot shows the distribution of data points between Revenue and Profit.
- We can observe how changes in Revenue relate to changes in Profit, which is essential for assessing the financial health of the business.

**Age Group Analysis: Profits**
The next part of the analysis focuses on Age Groups and their relationship with Profits. A box plot displays the distribution of profits within each Age Group.



*Insights:*
- This box plot helps us understand how profits are distributed among different age groups of customers.
- It can reveal whether specific age groups are more profitable, allowing for targeted marketing or product offerings.

**Multiple Subplots: Year, Customer Age, Order Quantity, Unit Cost, Unit Price, Profit**
The analysis then explores multiple subplots for various columns: Year, Customer Age, Order Quantity, Unit Cost, Unit Price, and Profit.

*Insights:*
- The subplots provide a visual representation of these variables, allowing for a quick overview of their distributions.
- Understanding these distributions can be valuable for identifying trends or outliers in the data.

**Conclusion:**
This analysis offers a visual understanding of the relationship between Revenue and Profit, insights into profit distribution across Age Groups, and a quick overview of various key columns. These visualizations are essential for decision-making and understanding the data from different perspectives.

Title: Data Visualization and Analysis

**Histogram: Revenue per Age**
In this section of the analysis, we focus on the distribution of "Revenue per Age." A histogram is used to display how revenue is distributed concerning different age groups.




*Insights:*
- The histogram provides insights into how revenue varies across different age groups.
- It helps identify which age groups contribute the most to the revenue, allowing for targeted marketing strategies.

**Calculated Cost and Profit**
The next part of the analysis deals with calculated cost and profit. We calculate the cost by multiplying "Order Quantity" by "Unit Cost." Understanding these values is crucial for assessing the cost structure and profitability
.

*Insights:*
- We calculate the cost of each order using the "Order Quantity" and "Unit Cost" columns.
- This information is fundamental for understanding the cost implications associated with sales.

**Conclusion:**
This analysis includes a histogram that shows how revenue is distributed across age groups, which can inform marketing decisions. Additionally, we calculated the cost of each order, providing valuable insights into the cost structure and its relationship with profit. Understanding these aspects is essential for managing costs and optimizing profitability.

 **Histogram: Revenue**
This section of the analysis focuses on the distribution of "Revenue." A histogram is used to visualize how revenue is distributed, offering insights into the sales data.



*Insights:*
- The histogram reveals the distribution of revenue across various transactions.
- It provides information on the frequency and range of revenue generated, which can be helpful for understanding sales patterns.

**Unit Price Adjustments**
Here, we examine the "Unit Price" column and perform adjustments. First, we display the initial values, and then we apply a 3% increase in unit prices.

*Insights:*
- The "Unit Price" column represents the prices of products.
- The 3% increase in unit prices simulates a pricing adjustment that can impact profitability.

**Conclusion:**
This analysis includes a histogram displaying the distribution of revenue, providing insights into the revenue patterns. Additionally, we demonstrate adjustments made to unit prices, which can be essential for understanding the impact of pricing changes on revenue and profit. These insights can be valuable for pricing and revenue optimization.

**Data Analysis Report: Kentucky State Customer Information**

This report focuses on customer data from the state of Kentucky. The data includes information about customers' age, gender, and purchase history. Let's delve into the insights derived from this dataset:

1. **Customer Demographics:**
   - The data consists of customers in the age group "Adults (35-64)," with an average customer age of 40.
   - All customers in this dataset are males, providing insights into gender representation.
   - These customers are located in Kentucky, a specific state within the United States.

2. **Product Information:**
   - Products purchased by these customers include items like "Hitch Rack - 4-Bike," "Fender Set - Mountain," "Sport-100 Helmet, Blue," and "ML Mountain Tire."
   - Various products were bought with different quantities, unit costs, unit prices, profits, and related costs.

3. **Financial Metrics:**
   - The revenue per age group varies, with "Adults (35-64)" generating an average revenue of $736.83.
   - The total number of transactions made by customers in the "Youth (<25)" and "Adults (35-64)" age groups is 73,652.

4. **Conclusion:**
   - This dataset provides valuable information about customers in Kentucky, including age, gender, and purchasing behavior.
   - Insights into product sales and financial metrics, such as revenue, profit, and cost, can be useful for optimizing marketing and sales strategies.
   - The dataset covers customers from different age groups, contributing to an understanding of their preferences and habits.
[Bike sales ANALYTICS.pdf](https://github.com/kikibyt/Bike_sales-_report/files/13209758/Bike.sales.ANALYTICS.pdf)


