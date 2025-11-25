# Interactive Dashboard: Measuring the Effectiveness of 2022 E-commerce Marketing Campaigns

## Summary

### *E-commerce Financial Performance Analysis 2022: Sales, Profit, and AOV Metrics*

### Insight 

* **Consistent Sales Peaks:** Sales consistently peak in late summer (August-September) but suffer a sharp, unseasonal decline towards the end of the year.
* **Product Dominance:** The "Mobiles & Tablets" category, led by brands like Samsung and Apple, is the primary revenue driver, but its high performance doesn't prevent a significant year-end slump.
* **AOV Spikes:** Sharp increases in Average Order Value (AOV) in April and September indicate periods of high-value purchasing, suggesting successful targeted promotions or product launches during those times.
* **Payment Preference:**  Customers overwhelmingly prefer Cash on Delivery (COD), indicating a potential lack of trust in digital payments or a preference for offline transactions.


### Recommendations 

* **Reinforce Peak Season Strategy:** Capitalize on the predictable August-September peak with aggressive promotions and ensure ample stock of top-selling products.
* **Mitigate Year-End Slump:** Investigate the causes of the post-September sales decline and implement targeted marketing campaigns to boost Q4 performance.
* **Promote Digital Payments:** Offer incentives (e.g., discounts, free shipping) and improve security guarantees to encourage customers to adopt digital payment methods.
* **Replicate AOV Success:** Analyze the products and strategies behind the AOV spikes in April and September to replicate that success and increase order value in other months.


### *Main Dashboard: 2022 Annual E-commerce Performance Overview* 

### Insight

* **Product Dominance:** The "Mobiles & Tablets" category is the primary revenue driver, with the highest total transactions in 2022. Within this category, Samsung and Apple are the top-performing brands.
* **Significant COD Preference:** The most popular payment method is Cash on Delivery (COD), with 1,809 unique orders in 2022, far exceeding any other payment option. This indicates a strong customer preference for offline payments.
* **Growth Across Segments:** The business experienced overall growth from 2021 to 2022. Several categories, including "Books" and "Others", showed an increase in total transaction value.
* **Strong Annual Performance:** The company achieved a strong performance in 2022 with a total sales value of $5.14 billion and a net profit of $1.08 billion.


### Recommendations 

* **Leverage Top Categories:** Focus marketing and promotional efforts on the "Mobiles & Tablets" category and top-selling brands like Samsung and Apple to maintain their market dominance.
* **Encourage Digital Payments:** Offer incentives, such as discounts or free shipping, to encourage customers to switch from COD to digital payment methods. This could improve operational efficiency and reduce logistical risks.
* **Optimize High-Value Products:** Analyze the top-selling products to understand what drives their success. Replicate these strategies to boost sales of other products and increase the overall average order value.
* **Invest in Growing Segments:** Develop specific strategies for categories that are showing growth, such as "Books," to diversify the product portfolio and reduce reliance on a few key categories.


## Data Visualization Project Goals 

The main objective of this project is to build a comprehensive and interactive dashboard that serves as a tool for the Marketing Team to analyze and measure the effectiveness of campaigns and overall business performance in 2022. This dashboard will be divided into several sections with the following specific goals:
* Main Dashboard for Business Performance Analysis:
  * To display key performance indicators (KPIs) such as Gross Sales, Net Profit, AOV (Average Order Value), and Active Customers.
  * To provide a quick and concise overview of the company's financial health and growth.
  * To enable the Marketing Team to monitor overall sales performance, profitability, and customer base growth.
* Detailed Dashboard for Category and Customer Behavior Analysis:
  * To present a more in-depth analysis with metrics like Product Name, Category, Net Profit, City, and others.
  * To provide insights into which products and categories are the most profitable.
  * To identify sales trends across different cities and understand customer purchasing patterns, which can be used for more effective market targeting strategies.
* Specific Dashboard for the Mobile & Tablets Category:
  * To create a specific visualization for the Mobile & Tablets category, which was the highest-selling category in 2022.
  * To analyze the performance of paylater payments within this category.
  * The purpose of this section is to help the Marketing Team understand purchasing behavior in the most dominant product segment and formulate specific promotional strategies for the paylater payment method.
Thus, this data visualization project will transform raw data from the database into easily understandable insights, allowing the Marketing Team to make more accurate, data-driven, and measurable strategic decisions.


## Data Source

For this data visualization project, we leverage a tailored e-commerce dataset that replicates a full year of operational data from 2022. While not based on actual data, this dataset is a rich representation designed to uncover sales patterns, measure profitability, and understand market trends. By combining the order_detail table, which logs every transaction, with sku_detail for product specifics and payment_detail for payment methods, we aim to transform raw data into a powerful business narrative. All insights will be visualized through an interactive dashboard created with Google Looker Studio, providing the Marketing Team with an essential tool for monitoring and evaluating performance.


## Problem Statements

Dear Data Analyst,Following up on yesterday's joint meeting, we will create a dashboard tomonitor and evaluate sales achievements each month. The dashboard willconsist of 2 pages and was created using lookerstudio.google.com.

1. The marketing team wants to see the development of the campaign in2022, what will the trend be like? An explanation is given and what the callto action is so that the team can make a decision in front of it. Dashboard inthe form of:
* The relationship between Value Sales (before discounts), Net Profit, and AOV(average order value).
  * Net profit = Value Sales (before discount) - (cogs * qty)
  * AOV = Value Sales (before discount) / Total Unique Order.
* There are slices for Order Date, Category, Sales Value, Transaction Value,Payment.
  * Value Transaction:
     - Valid → is_valid = 1
     - Not Valid → is_valid = 0
  * Payment → payment_method
 

## E-commerce Financial Performance Analysis 2022: Sales, Profit, and AOV Metrics


![alt text](https://github.com/restianimutoharoh/Interactive-Dashboard-Measuring-the-Effectiveness-of-2022-E-commerce-Marketing-Campaigns/blob/master/E-commerce%20Financial%20Performance%20Analysis%202022.png?raw=true) 


### Insight

* **Consistent Annual Sales Patterns:** The data reveals a clear seasonal pattern, with sales and profit peaking in specific months. In 2021, the peak occurred in August. A similar trend repeated in 2022 with significant peaks in April and August/September, indicating a predictable purchasing cycle.
* **Category and Brand Dominance:** The "Mobiles & Tablets" category is a proven primary revenue driver in 2022, contributing the largest portion of total transactions. Within this category, Samsung and Apple brands significantly dominate the market, holding the top positions based on total transaction value.
* **AOV and Year-End Sales Anomaly:** There are sharp spikes in AOV (Average Order Value) in April and September 2022. This suggests that customers made significantly larger purchases than usual during those specific months. However, a concerning trend is the drastic decline in sales and profit after September, which continued into the year's end, contradicting the typical holiday season sales spike in the e-commerce industry.
* **Strong Non-Digital Payment Preference:** The Cash on Delivery (COD) payment method is overwhelmingly more popular than all other digital options. This dominance highlights that a large portion of the customer base may have a strong preference for cash, concerns about online transaction security, or limited access to digital banking services.


## Problem Statements

Can show: 
* The table contains: Product Name, Category, Before Discount, After Discount, Net Profit, Quantity , Customer (unique value). 
* There are slicers: Order Date, Category, TransactionValue, Payment
* Scorecard: Before Discount, After Discount, Net Profit, Quantity, Customer (unique value), AOV.
2. During 2022, display the mobile & tablet categories that havemade payments via jazzwallet.What are the quantities and customers?
3. Make a chart based on dashboard number 2.


## Main Dashboard: 2022 Annual E-commerce Performance Overview


![alt text](https://github.com/restianimutoharoh/Interactive-Dashboard-Measuring-the-Effectiveness-of-2022-E-commerce-Marketing-Campaigns/blob/master/Main%20Dashboard%202022%20Annual%20E-commerce%20Performance%20Overview.png?raw=true) 


### Insight

* **Strong Overall Business Performance:** In 2022, the company achieved a total sales value of $5.14 billion and a net profit of $1.08 billion. The high Average Order Value (AOV) of $1.61 million indicates that customers tend to make large-value purchases, which significantly contributes to revenue.
* **Dominant Categories and Brands Drive Sales:** The "Mobiles & Tablets" category is the main revenue driver, with Samsung having the highest total transactions, followed by Apple. This is supported by dashboard data showing that a "Mobiles & Tablets" product, IDROID_BALRX7-Gold, is a top-selling item.
* **Growth Across Various Category Segments:** The company shows growth across multiple categories from 2021 to 2022. Although the status data is inconsistent, the raw transaction values indicate that several categories, such as "Books" and "Others," experienced an increase in total transaction value.
* **Payment Preference Skews Towards COD:** Despite generating significant revenue, a large portion of customer transactions still rely on the Cash on Delivery (COD) payment method. With 1,809 unique orders, COD significantly outweighs digital payment methods like Payaxis, which had only 181 orders.
