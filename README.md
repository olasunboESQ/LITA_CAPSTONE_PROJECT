# LITA_CAPSTONE_PROJECT

MY FINAL PROJECT @ INCUBATOR LITA TRAINING

### Project Overiew

This Project contains a Dataset namely:

- Sales Data

This is a Sales Performance Analysis for a Retail Store
I am tasked with analyzing the sales performance of a retail store using the following Data Analysis tools:
i. Microsoft Excel 
ii. Structured Query Language
iii. Microsoft PowerBI

I am to explore the Sales Data to uncover key insights such as top-selling products, regional
performance, and monthly sales trends. With my Excel tool i will 
- Perform an initial exploration of the sales data.
- Use pivot tables to summarize; Total sales by product, region, and month.
- Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
- Create any other interesting report.
  
### OUTCOME OF PROJECT 1(SALES DATA) USING MICROSOFT EXCEL 

The first thing I did was to calculate the revenue for each of the row on the Sale Dataset by multiplying the Quantity row by the UnitPrice row

For the result i got from the dataset worked on

[githubsales.xlsx](https://github.com/user-attachments/files/17611792/githubsales.xlsx)


For easier visualization I added a screenshoot of my outcome

![Screenshot (15)](https://github.com/user-attachments/assets/6b361139-27fb-49a5-8d1a-359eec088c9b)

I thereaffter went on to use Pivot Table to create beautiful and interesting reports showcasing 

a. Total Sales by Product
b. Total Sales by Region
c. Total Sales by Month
d. Top-Selling Product
e. Average Sales by Product

          TOTAL SALES BY PRODUCT	
![image](https://github.com/user-attachments/assets/de5a50f4-f34f-4a56-a27f-6c69a39fae66)

         TOTAL SALES BY REGION	
![image](https://github.com/user-attachments/assets/2b3e18a2-0533-4039-b23c-51fff26718e5)


         TOTAL SALES BY MONTH	
![image](https://github.com/user-attachments/assets/786dcd11-3d6b-4e58-afb3-d0c3aa2dd5ac)


        TOP SELLING PRODUCT BY REVENUE					
![image](https://github.com/user-attachments/assets/6947daa6-a0cf-4760-b313-f58ebc403ac4)


        TOP SELLING PRODUCT	
![image](https://github.com/user-attachments/assets/db5ab314-e904-419b-9f0c-e14567f14cfc)


          AVERAGE SALE PER PRODUCT BY REVENUE		
![image](https://github.com/user-attachments/assets/fb6c2837-1dd0-411b-81f0-fb636aa067c6)


         AVERAGE SALES PER PRODUCT		
![image](https://github.com/user-attachments/assets/5e6c2630-bcf2-4e22-b185-a9aca8235802)


### Structured Query Language

This is the second Analysis tool I used in exploring the Sales Dataset in this project. SQL means standard language for accessing, managing and modifying data in a relational dtatabase.

I used the SQL Tool to answer the following questions after I had successfully imported my data into a database i created which I named LITA_DB.

o retrieve the total sales for each product category.
o find the number of sales transactions in each region.
o find the highest-selling product by total sales value.
o calculate total revenue per product.
o calculate monthly sales totals for the current year.
o find the top 5 customers by total purchase amount.
o calculate the percentage of total sales contributed by each region.
o identify products with no sales in the last quarter.

I ran various codes in order to be able to extract the neccesary information i meeded which are embedded in the Salesdata Table on my LITA_DB

```sql
select *from[dbo].[SalesData]

........TOTAL REVENUE PER PRODUCT.......
SELECT sum (revenue)as totalsale4hat FROM SalesData WHERE PRODUCT = 'HAT'

SELECT sum(revenue) as totalsale4shoes FROM SalesData WHERE PRODUCT = 'SHOES'

SELECT sum(revenue) as totalsales4shirt FROM SalesData WHERE PRODUCT = 'SHIRT'

SELECT sum(revenue) as totalsales4gloves FROM SalesData WHERE PRODUCT = 'GLOVES'

SELECT sum(revenue)as totalsales4socks FROM SalesData WHERE PRODUCT = 'SOCKS'

SELECT sum(revenue) as totalsale4jacket  FROM SalesData WHERE PRODUCT = 'JACKET'



- Find The Number Of Sales Transactions In Each Region.

SELECT REGION,
count(orderid)as regionalsales from [dbo].[SalesData] 
GROUP BY REGION
ORDER BY regionalsales DESC


- HIGHEST SELLING PRODUCT BY TOTAL SALES VALUE

select top 1 (product),
sum (revenue) as totalsales from [dbo].[SalesData]
group by product





3. Power BI:
o Create a dashboard that visualizes the insights found in Excel and SQL. The
dashboard should include a sales overview, top-performing products, and
regional breakdowns.
Project 2: Customer Segmentation for a Subscription Service
Summary: This project involves analyzing customer data for a subscription service to identify
segments and trends. Your goal is to understand customer behavior, track subscription types,
and identify key trends in cancellations and renewals. The final deliverable is a Power BI
dashboard that presents your analysis.
Instructions:
1. Excel:
o Analyze customer data using pivot tables to find subscription patterns.
o Calculate the average subscription duration and identify the most popular
subscription types.
o Create any other interesting reports.
2. SQL:
Hint – You need to load the dataset into your SQL Server environment to write
and validate your queries.
Write queries to extract key insights based on the following questions.
o retrieve the total number of customers from each region.
o find the most popular subscription type by the number of customers.
o find customers who canceled their subscription within 6 months.
o calculate the average subscription duration for all customers.
o find customers with subscriptions longer than 12 months.
o calculate total revenue by subscription type.
o find the top 3 regions by subscription cancellations.
o find the total number of active and canceled subscriptions.
3. Power BI:
o Build a Power BI dashboard that visualizes key customer segments,
cancellations, and subscription trends. Include slicers for interactive analysis
