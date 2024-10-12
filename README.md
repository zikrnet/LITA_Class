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

N.B: Row 1,048576,  Column 16,384
---
# Basic Excel Functions

1. SUM
The Excel SUM function returns the sum of all inserted values. For the input, you can combine any sort of numerical values, e.g. numbers, cell references, ranges or arrays.
```
SUM (number1, [number2], [number3], …)
```
2. AVERAGE
The Excel AVERAGE function returns the average of all inserted values. For the input, you can combine any sort of numerical values, e.g. numbers, cell references, ranges or arrays.
```
Syntax: AVERAGE (number1, [number2], [number3], …)
```
3. IF FUNCTION
The Excel IF function is the most essential function in Excel for logical tests. You can define the value that is returned by this function if the result of the logical test is TRUE and the value that is returned if the result is FALSE. If you want to test more than one condition, you can simply nest multiple IF functions.
```
Syntax: IF  (logical_test, [value_if_true], [value_if_false])
```
4. MIN & MAX Function
The Excel MIN function returns the smallest numeric value in a range of values. Accordingly, the Excel MAX function returns the biggest numeric value in a range of values. Both function only consider numeric values. Empty cells, logical or text values will be ignored.
```
Syntax: MIN (number1, [number2], …)    |      MAX (number1, [number2], …)
```

5.
6. COUNT
7. 4. COUNTA
8. IF
9. TRIM
10. MAX & MIN.




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
