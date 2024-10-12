# NAVIGATING THE DIGITAL ECONOMY:OPPORTUNITIES FOR LADIES IN AFRICA

## Project Title: BASICS OF DATA ANALLYSIS


## Project Overview
---
E-commerce project management is the process of planning, organizing, and executing tasks and resources to achieve specific goals within the e-commerce space. ECommerce project management is a subset of regular project management that has a different focal point and its own characteristics.

### Data Sources
---
E-commerce Project Management for Rapid Growth [Learn More](www.blog.datahut.co/post/ecommerce-data-sources-to-scrape)

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. Data Cleaning
  2. Analysis and
  3. Visualization
- SQL - Strutured Query Language
  1. for Query of Data
- GitHub
  1. for Portfolio Building

### Data Cleaning and Preparation
---
Data cleaning and preparation in Excel involves the following steps;
1. Remove duplicates: Duplicate entries can sneak into your data when copying and pasting from various sources.
2. Standardize formats: Inconsistent formatting can hinder data analysis.
3. Clean text data: Text data often harbors errors like typos, extra spaces, and inconsistent capitalization.
4. Fill missing values: Missing values can plague your data.
5. Use data validation.
6. Apply conditional formatting.
7. Utilize Power Query.


### Exploratory Data Analysis
To perform exploratory data analysis (EDA), follow these steps123:
1.  Observe your dataset at a high level.
2.  Find any missing values.
3.  Categorize your values.
4.  Find the shape of your dataset.
5.  Identify relationships in your dataset.
6.  Locate any outliers in your dataset.

### Data Analysis 
This is where we include some basic lines of code or queries or even some of the DAX expressions used during analysis;

```
SQL

SELECT * FROM TABLE1
WHERE CONDITION = TRUE
```


```
SQL
SELECT * FROM CUSTOMERS ORDER BY
COUNTRY, CITY;
```
![](https://github.com/zikrnet/LITA_Class/blob/main/bar%20chart.jpg)


### CUSTOMERS
select all records where the customerID column has the value 32

```
SQL
SELECT * FROM CUSTOMERS WHERE CUSTOMERID = 32,
```

![](https://github.com/user-attachments/assets/1bfd39ce-b795-42b4-8b20-81034c2a0123)

## CUSTOMER'S TABLE
select all records from the customers table, sort the result alphabetically, first by the column country, then by the column city

```
SQL
SELECT * FROM CUSTOMERS ORDER BY
COUNTRY, CITY;
```
![chart github](https://github.com/user-attachments/assets/385b2ffd-d43c-4f38-8eb0-1914acdf2c00)
