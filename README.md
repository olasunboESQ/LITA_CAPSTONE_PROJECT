# LITA_CAPSTONE_PROJECT

MY FINAL PROJECT @ INCUBATOR LITA TRAINING

###Project Overiew

The Project contains a Dataset namely:

- Sales Data

In Project : Sales Performance Analysis for a Retail Store
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
  
###OUTCOME OF PROJECT 1(SALES DATA) USING MICROSOFT EXCEL 

The first thing I did was to calculate the revenue for each of the row on the Saled Dataset by multiplying the Quantity row by the UnitPrice row
F2*G2= REVENUE
I then proceed to use the AverageIf function to calculate the avearge sales per product and Sumif to calculate total revenue for region

![Screenshot (15)](https://github.com/user-attachments/assets/6b361139-27fb-49a5-8d1a-359eec088c9b)

I thereaffter went on to use Pivot Table to create beautiful and interesting reports showcasing 
a. Total Sales by Product
b. Total Sales by Region
c. Total Sales by Month
d. Top-Selling Product
e. Average Sales by Product

    TOTAL SALES BY PRODUCT	
Row Labels	Sum of Revenue
Gloves	296,900
Hat	316,195
Jacket	208,230
Shirt	485,600
Shoes	613,380
Socks	180,785
Grand Total	2,101,090
![image](https://github.com/user-attachments/assets/7963cdb4-7c12-42b1-9cd2-ccbadd9777e0)

  TOTAL SALES BY REGION	
Row Labels	Sum of Revenue
East	485,925
North	387,000
South	927,820
West	300,345
Grand Total	2,101,090
![image](https://github.com/user-attachments/assets/62d091fe-949b-4a42-9cef-f7c233e40246)

    TOTAL SALES BY MONTH	
Row Labels	Sum of Revenue
2023	
Jan	49,600
Feb	247,500
Mar	52,395
Apr	7,425
May	59,640
Jun	99,400
Jul	237,600
Aug	29,880
Sep	34,720
Oct	133,920
Nov	103,950
Dec	49,300
2024	
Jan	198,400
Feb	298,800
Mar	54,780
Apr	39,440
May	44,640
Jun	148,200
Jul	37,200
Aug	174,300
Grand Total	2,101,090
![image](https://github.com/user-attachments/assets/152c0c59-2be6-4fe3-b148-1fa77a5f10a2)









The goal is to produce an interactive Power BI
dashboard that highlights these findings.
Instructions:

2. SQL:
Hint – You need to load the dataset into your SQL Server environment to write and
validate your queries.
Write queries to extract key insights based on the following questions.
o retrieve the total sales for each product category.
o find the number of sales transactions in each region.
o find the highest-selling product by total sales value.
o calculate total revenue per product.
o calculate monthly sales totals for the current year.
o find the top 5 customers by total purchase amount.
o calculate the percentage of total sales contributed by each region.
o identify products with no sales in the last quarter.
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
