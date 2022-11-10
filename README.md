# Sales Insights of Atliq hardware 

I used SQL queries in MySQL Workbench to take a look into the data and Power BI for ETL and visualizations to create the insights.

## Overview
The company head office is based in Delhi  with multiple offices across India.

*	The database contains 5 tables: customers, date, markets, products, and transactions.
*	There are 17 markets, 279 products, and 38 customers.
*	The observation period is from january 2018 to june 2020.
*	The total revenue in 2020 was $ 142,23 Mi, 42% less than 2019, which was $ 336,45 Mi.
*	Most of the transactions data are in INR currency, but we have 4 records in U$ currency.
  And we got Paris and New York on the “sales markets” table. We’re going to deal with it in the ETL process.
  
## ETL
After I have explored the data and its basic features using Mysql I imported the MySql database into the PowerBi for data transformation.

## Data modeling

![rsz_screenshot_2022-11-10_172407](https://user-images.githubusercontent.com/90148389/201166511-e281e012-9e64-46fe-a7bb-3176f2cf4acd.png)


