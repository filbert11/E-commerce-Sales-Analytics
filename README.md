# E-commerce Sales Analytics

## Introduction
Sales is the most important factor in e-commerce company as it generates revenue from the platform fee from each transaction.

In this project, we aim to *Explore* order items data to find interesting insights to Olist to improve their sales.

This data used is Brazilian E-Commerce Public Dataset by Olist which is download from https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data
Only data in year 2017 is used in this project as the data in year 2016 and 2018 are incomplete.

## Exploratory Data Analysis
Most of the transactions are made after 11 AM until midnight.
![TransactionTime](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/transactions_time.jpeg)

November is the month with the highest transactions, it is probably due to customers stocking up for Christmas.
![TransactionMonths](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/sales_time_series.jpeg)

Review score of the product does not correlate to higher no of sales.
![ReviewScoreCorrelation](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/review_score_sales_correlation.jpeg)

Top 10 products category with highest sales
![TopSalesProducts](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_sales_product_category.jpeg)

Top 10 customer cities and states with highest sales
![TopCustomerCities](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_city.jpeg)
![TopCustomerStates](https://github.com/filbert11/ecommerce-sales-analytics/blob/main/plot/top_customers_state.jpeg)

## Conclusion
These are the findings from the e-commerce analytics:
- Most of the transactions happen from 10 AM till midnight. If the merchants want to do flash sale, they need to do it after 10 AM for effective marketing
- November is the month with highest transactions. The merchants should aim to clear their stocks at this month
- High review score does not translate to higher sales of products
- These are the top 10 products category with highest sales on the platform: bed_bath_table, sports_leisure, health_beauty, furniture_decor, computers_accessories, toys, housewares, cool_stuff, watches_gifts, telephony. New merchants or existing merchants can aim to expand to these products category to increase their overall sales
- Top 3 sales are made from customers from these cities: sao paulo, rio de janeiro, and belo horizonte. Similarly, top 3 sales are made from these states: SP, RJ and MG. Merchants would want to target these cities or states to boost overall sales
