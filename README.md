# AtliQ Hardware Consumer Goods: Ad-Hoc-Insights

## Project Overview and Problem Statement

Atliq Hardware is one of the leading computer hardware producers in India and well expanded in other countries too. specializes in selling computers and accessories.

The management noticed that they did not get enough insights to make quick and smart data-informed decisions. 
However, The Data Analytics Director wants to expand their data analytics team by adding several junior data analysts. So he decided to conduct a SQL challenge which will help him understand both tech and soft skills

Now the company wants insights for 10 ad hoc / business requests.


## Data Structure/ Data Modeling and Tools

The 'gdb023' (atliq_hardware_db) database was provided to me to work on and it includes six main tables:

1. dim_customer: contains customer-related data
1. dim_product: contains product-related data
1. fact_gross_price: contains gross price information for each product
1. fact_manufacturing_cost: contains the cost incurred in the production of each product
1. fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
1. fact_sales_monthly: contains monthly sales data for each product.


**Tools used** 

* I used My SQL to answer the questions 
* and Power BI for visualization

## 10 Ad-Hoc Requests and Answers:

### 1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region.

### 2. What is the percentage of unique product increase in 2021 vs. 2020? The final output contains these fields, unique_products_2020, unique_products_2021, percentage_chg

### 3. Provide a report with all the unique product counts for each segment and sort them in descending order of product counts. The final output contains 2 fields, segment product_count

### 4. Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? The final output contains these fields, segment product_count_2020, product_count_2021, difference

### 5. Get the products that have the highest and lowest manufacturing costs. The final output should contain these fields, product_code, product, manufacturing_cost

### 6. Generated a report that contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market. The final output contains these fields, customer_code, customer, average_discount_percentage


### 7. Got the complete report of the Gross sales amount for the customer “Atliq Exclusive” for each month. This analysis helps to get an idea of low and high-performing months and make strategic decisions. The final report contains these columns: Month, Year, Gross sales Amount


### 8.In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity, --> Quarter, total_sold_quantity


### 9. Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? The final output contains these fields --> channel, gross_sales_mln, percentage


### 10. Got the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? The final output contains 

===============================================================================================================

**NOTE-**

Atliq hardware ad-hoc insights presentation pdf - In this file, you will find the presentation


