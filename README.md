# Capstone-Project-2---Olamiposi-G-Aleoluwa
In this project, I was tasked with analyzing customer data for a subscription service to identify segments and trends. The goal is to produce an interactive Power BI dashboard that highlights these findings

# LITA-Capstone-Project 2---Olamiposi-G-Aleoluwa
In this project, I was tasked with  analyzing customer data for a subscription service to identify  segments and trends. The goal is to produce an interactive Power BI  dashboard that highlights these findings

## Project 2 Title - Subscription Service Analysis

### Table of Content
[Project Overview](#project-overview)

[Data Sources](data-sources)

[Data Cleaning and Preparations](data-cleaning-and-preparation)

[Data Analysis](data-analysis) 

### Project Overview
In this project, I was tasked with analyzing the customer data for a subscription service to identify 
segments and trends. Your goal is to understand customer behavior, track subscription types, 
and identify key trends in cancellations and renewals. The final deliverable is a Power BI 
dashboard that presents your analysis.

### Data Sources
The primary source of data used is Customer Data.csv which was provided as part of the instruction

### Tools Used 
- Microsoft Excel for
   1. Data Cleaning
   2. Analysis.
- Structured Query Language (SQL) for Quring of Data.
- Power BI for Visualization
- GitHub for Portfolio Building

### Data Cleaning and Preparations
I performed the following actions in the cleaning phase
   1. Data Loading and Inspection
   2. Handling missing variables
   3. Data Cleaning and formatting

### Exploratory Data Analysis 
This involved exploring the data to answer some questions about the Data such as;
 - Summarizing the sales data to show total sales by product, region, and month using pivot tables 
 - Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.



### Data Analysis 
This is where I queried my data 

```SQL
SELECT *
FROM [dbo].[Customer Data]
```
To Retrieve the total sales for each product category

```SQL
SELECT Product,SUM(Quantity) as Total_Sales
FROM [Sale Data]
GROUP BY Product
```


### Data Visualization




