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
5. TRIM Function
The Excel TRIM function removes the leading and trailing spaces from a given text. Additionally, it removes unnecessary spaces between words.
```
Syntax: TRIM (text)
```
6. CONCATENATE Function
The Excel CONCATENATE function joins two or more text items together.
```
Syntax: CONCATENATE (text1, [text2], …)
```
---
## 4. REPORT AND DASHBOARD IN EXCEL
An Excel dashboard is basically a high-level visual representation of key business metrics.

## Steps to Create a Dashboard in Excel
Here’s a simple set of steps to follow to create an Excel dashboard:
- Step 1: Pull your raw data into Excel
If your data already exists in an Excel spreadsheet, go ahead and skip this step. If not, here are some ways to import data into Excel:
1. Simply copy and paste
2. Use Microsoft PowerQuery to import data from different sources like CSV files, PDFs, tables, folders, SQL servers, and many more platforms.

- Step 2: Set up a structure for your workbook
Keep your dashboard at the beginning of your new Excel workbook, and add one or more worksheets with your data in them. Name your first sheet ‘Dashboard’ and the other tab ‘Data’ for easy reference.

- Step 3: Create a table
Creating a table isn’t a mandatory step, but it makes the process of creating charts much more efficient. Tables have the ability to expand as you add new data and perform calculations easily.

First select the data and go to Insert>Table. Excel will automatically create a table, and you can apply your preferred table style. Give your table an appropriate name so you can reference it easily instead of having to select the data range every time.

- Step 4: Visualize your data
There are many ways to analyze your data on Excel, and you should go for the option that suits the overall goal for the dashboard. Here are the commonly used methods of visualizing data:
1. Pivot Table
2. Charts
3. Excel Formulas
4. Conditional formatting
5. Pivot tables are the most useful method for the purposes of a dashboard, as they let you sort, group, count, and add up data in a table.

- Step 5: Create a Pivot Table
Use a new worksheet on Excel to do this, since it can take some time to figure out properly. In the worksheet, go to Insert>PivotTable, and enter the name of your table.
Arrange the table fields depending on what you want to see. Now you can insert a PivotChart based on the PivotTable. You could also go with a pie chart, bar graph, Gantt chart, waterfall chart, stacked column chart, line graph, and more.
---

---
## MICROSOFT EXCEL - DATA ENTRY IN EXCEL 
Data Entry Form is a form that helps to enter the data with the help of a form in which the data can be added, searched, and previous data can be deleted.



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
