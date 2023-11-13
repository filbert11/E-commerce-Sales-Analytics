# E-commerce Sales Analytics

## Introduction
Sales is the most important factor in e-commerce company as it generates revenue from the platform fee from each transaction.

In this project, we aim to *Explore* order items data to find interesting insights to Olist to improve their sales.

This data used is Brazilian E-Commerce Public Dataset by Olist which is download from https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data.
Only data in year 2017 is used in this project as the data in year 2016 and 2018 are incomplete.

## Exploratory Data Analysis
Most sales happen after 10:00 AM and lasted until 12:00 AM midnight
<br> ![TransactionTime](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/transactions_time.jpeg)

November is the month with the sales, it is probably due to the upcoming festive season like thanksgiving festival and christmas. November is also the month of Black Friday which is one of the largest sale of the year.
<br> ![TransactionMonths](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/sales_time_series.jpeg)

Majority of the payments made in the platform is via credit_card follows by boreto (Boleto bancário) which is an official Brazilian payment method regulated by the Central Bank of Brazil
<br> ![TopPaymentMethods](https://github.com/filbert11/E-commerce-Sales-Analytics/blob/main/plot/payment_methods.jpeg)

Review scores of the sellers/products do not correlate to higher no of sales with correlation score of <0.01. However, products/sellers with higher sales lies on review_score between 3.5-4.5.

Correlation of sellers review_score with sales
<br> ![SellerReviewScoreCorrelation](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/seller_review_score_sales_correlation.jpeg)

Correlation of products review_score with sales
<br> ![ProductReviewScoreCorrelation](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/product_review_score_sales_correlation.jpeg)

Top 10 products category with highest sales
<br> ![TopSalesProducts](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_sales_product_category.jpeg)

Top 10 products category with highest Average Order Value (AOV)
<br> ![TopAOVProducts](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_aov_product_category.jpeg)

Top 10 customer cities and states with highest sales and their percentage
<br> ![TopCustomerCities](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_city.jpeg) ![TopCustomerCitiesPct](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_city_pct.jpeg)
<br> ![TopCustomerStates](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_state.jpeg) ![TopCustomerStatesPct](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_state_pct.jpeg)

Customer retention rate is 0 for Olist in 2017
<br> ![CustomerRetentionRate](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/repeated_customers_pct.jpeg)

Active sellers are increasing throughout the year and have similar trend with no of sales
<br> ![CustomerRetentionRate](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/sellers_time_series.jpeg)

## Insights and Findings
These are the insights and findings from the e-commerce analytics:
- Most of the transactions happened from 10 AM till midnight
- November is the month with highest transactions
- High review scores of sellers/products do not translate to higher sales with correlation score < 0.01. Despite low correlation score, there are more sales happening on products with review score between 3.5-4.5
- Top payment methods are credit_card follows by boreto
- These are the top 10 products category with highest sales on the platform: bed_bath_table, furniture_decor, sorts_leisure, health_beauty, computers_accessories, housewares, toys, garden_tools, cool_stuff and watches_gifts
- bed_bath_table has the highest sales but it is not the highest AOV which means customers purchased more bed_bath_table items but does not spend more money on these items. Instead, customers spend more money on computer_accessories
- Top 3 sales are made from customers from these cities: sao paulo, rio de janeiro, and belo horizonte. Similarly, top 3 sales are made from these states: SP, RJ and MG. Merchants would want to target these cities or states to boost overall sales as majority customers live here
- There is 0 customer retention in 2017
- More sellers become more active on Olist and more sales happening when there are more sellers

## Product Design and Recommendation
There are the recommendations that Olist can take to improve overall sales:
- Merchants need to do flash sales after 10 AM for effective marketing as most transactions happen after 10 AM till midnight
- Merchants should allow customers to make payments by these two methods namely credit_card and boreto to stay competitive in the market
- Merchants should aim to get ratings between 3.5-4.5 as most sales happen to product/seller with this review score. Olist should incentivise customers to give review score on the platform
- Olist should create a loyalty programme to improve its customer retention rate
- 42% customers stay at sao paolo contributes follows by 22% customers stay at rio de janeiro. Olist should prioritise these cities in their sales strategy like sales, better shipping, etc.
- The higest profitable items (high AOV) are not the top sales items on Olist. Olist should consider promoting these high AOV product_category more on the platform to improve overall revenue
