# NAVIGATING THE DIGITAL ECONOMY:OPPORTUNITIES FOR LADIES IN AFRICA

## Project Title: BASICS OF DATA ANALLYSIS

## AGENDA

1. Foundations of Data
2. Introduction to Ms-Excel
3. Basic Excel Functions
4. Reports and Dashboards in Excel
5. Project
---
## QUOTES: The capacity to learn is a gift; the ability to learn is a skill; the willingness to learn is a choice. - Brian Herbert
---
## 1. FOUNDATIONS OF DATA
A data foundation refers to the fundamental infrastructure, processes, and strategies that lay the groundwork for effectively collecting, managing, storing, organizing, and leveraging enterprise data. A data foundation will allow you to consider your data as a single entity, rather than disparate, largely unrelated pieces of information.
---

## 2. Introduction to Ms-Excel
Microsoft Excel is a popular spreadsheet software program for business. It's used for data entry and management, charts and graphs, and project management. Excel contains the workbook where we see multiple worksheets

![Excel_Cells_Explained](https://github.com/user-attachments/assets/95b2718a-d1a3-4363-b396-0ed6e7dbdc41)

---
oft Excel [Download Here](https://www.microsoft.com)
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
