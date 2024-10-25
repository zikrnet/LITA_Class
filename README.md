## Project Title: BASICS OF DATA ANALYSIS

# PROJECT OVERVIEW
1. Data Source
2. Tools Used
3. Data Cleaning and Preparation
4. Exploratory Data Analysis
5. Data Analysis
It ivolves outlining key aspects of the project, including its objectives, methodology, data sources, analysis techniques, and expected outcomes.

# Data Sources
1. Source: Where the data is coming from (e.g. internal databases, third party services, surveys)
2. Type: Structured, unstructured, time-series etc
3. Time Frame: The period the date covers (e.g. last yeat, last quarter)

# Methodology
Methods and Tools used for the analysis;
- Data Cleaning:       Outline the processes for preparing the data (handling missing values, outlier detection etc)
- Analysis Technique:  Specify the analytical methods
- Tools and Software:  Ms- Excel, SQL and PowerBI

## AGENDA

1. Foundations of Data
2. Introduction to Ms-Excel
3. Basic Excel Functions
4. Reports and Dashboards in Excel
5. Project
---

## QUOTES: The capacity to learn is a gift; the ability to learn is a skill; the willingness to learn is a choice. - Brian Herbert

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


## MICROSOFT EXCEL - DATA ENTRY IN EXCEL 
Data Entry Form is a form that helps to enter the data with the help of a form in which the data can be added, searched, and previous data can be deleted.

# Dataset Description
These data fields collectively provide information about the following;
- Sales Transaction
- Enabling Analysis of Sales Performance
Across different regions, markets, stores, products and time periods

# Data Source
This is a public dataset that was downloaded from Kaggle

# Data Fields
1. Region:       The geographic region where the store is located
2. Market:       The specific market or city where the stores is located
3. Store:        A unique identifier for each individual store
4. Trade Date:   The date of the transaction sale
5. Fiscal Period: e.g. quarter, month to which sales begin
6. Model:         model being sold
7. Line of Business: where business category belongs
8. Day Category:  e.g. weekdays, weekend etc
9. Revenue:       The total revenue generated by the sale, typically calculated by multiplying the quantity sold by the unit price
10. Units Sold:    The number of units of the product sold in the transaction  

# DATA VISUALISATION
The following images shows the pivot tables used in building the dashboard that shows the overview of the sales performance of the different regions;

# Revenue by Region
- North East: is the top performing region. Generating the highest revenue of 18.64M
- South West: with a revenue of 15.88M
- North Central: is the lowest performing region with a revenue of 6.49M

![IMG_20241012_204719](https://github.com/user-attachments/assets/fb280efc-6ac0-4c50-80d7-252e7afcc681)

# Unit Cost by Region
- North East:  is the top performing region, selling the highest number of units (208,983)
- South West:  followed by (169,730)
- North Central: is the lowest performing region with only (54,522) units sold

![IMG_20241012_204700](https://github.com/user-attachments/assets/e496ff5e-ea68-4393-b1f6-d097474c2f8c)

# Top Stores in the Region
**Ajaokuta** and **Ankpa** are the top performing stores, generating significantly higher revenue compared to other stores. The remaining stores have similar revenue levels, with Ekiti South West being the highest among them.

![IMG_20241012_204642](https://github.com/user-attachments/assets/f77b58c5-e454-43de-a946-d55a3a168627)

# INTRODUCTION TO SQL
## STRUCTURED QUERY LANGUAGE - SQL
It is used for storing and managing data in RELATIONAL DATABASE MANAGEMENT SYSTEM (RDBMS). It is a standard language for relational database system. It enables a user to relate databases and tables. 
SQL allows user to query the database in a number of ways, using English-Like Statements. 

**Note: SQL is used for storing, retrieving and managing data in a relational database management system.** 

## What are the SQL?
SQL follows the following rules;
- Structure query language is not a case sensitive
- Statements of SQL are dependent on text lines. We can use a single SQL
- Using the SQL statements, you can perform most oof the actions in a database
- SQL depends on tuple relational calculus and algebra

## What is the Databases?
A database is an organised collection of data that is stored and managed in a structured way to allow for easy access, retrieval and manipulation.

## Advantages of Database
- Data Integrity
- Security
- Backup and Recovery
- Concurrency
- Scalability
- Efficient Data Management

## How Databases store Data?
Databases store data in a structured format using tables; which are composed of rows and columns

Note: Database tables for instance are organized by columns
- Row is called Records
- Column is called Fields
- Each column must have a UNIQUE IDENTIFIER

## Why SQL?
1. SQL is easy to understand
2. Traditional databases

## Basic SQL Commands
1. SQL commands are instructions used to communicate with database
2. It also perform specific task, function and queries of data

## Types of SQL Commands and their examples
1. Data Definition Language:     CREATE, ALTER, DROP, TRUNCATE
2. Data Manipulation Language:   INSERT, UPDATE, DELETE
3. Data Control Language:        GRANT, REVOKE
4. Data Query Language:          SELECT
5. Transaction Control Language: COMMIT, ROLLBACK, SAFE POINT

## Data Type
Is used to define a value that a column can contain
- String
- Numeric
- Boolean
- Date/DateTime

# Microsoft SQL Server Management Studio 
Is a software application developed by Microsoft that is used for configuring, managing, and administering all components within Microsoft SQL Server. 
SQL Server Management Studio (SSMS) is a windows software or a client tool used to connect and work with our SQL Server from a graphical interface instead of using the command line. Microsoft SQL Server 2005 launched the management studio to work with SQL Server and Azure SQL databases. [https://www.javatpoint.com/sql-server-management-studio]

# Interface of Microsoft SQL Server Management Studio
![sql server](https://github.com/user-attachments/assets/a4f710c4-80dd-4c3f-84f8-f12babda2f4e)
---

# Writing SQL Queries
1. Create a Table
```
create database LITA_DB
```

2. Create Employee Table
```
CREATE TABLE Employee (
staffid varchar (225) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
```

3. Select:  helps to retrieve information from database
Syntax

```
select * from employee
```

4. Insert:  to key-in data in the database
Syntax

```
insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
```

5. Drop Table:  to delete the entire table in a database
Syntax

```
drop table employee
```

6. Delete:  will erase the record
Syntax

```
DELETE FROM table_name WHERE condition
```
Note: Be careful when deleting records in a table! Notice the WHERE clause in the DELETE statement. The WHERE clause specifies which record(s) should be deleted.

7. Truncate:  a DDL or Data Definition Language command that is used to delete the complete data from the table without deleting the table structure
Syntax

```
TRUNCATE TABLE Tb_name
```
8. Identity:  is to auto increment and it will be increasing by (1).
Syntax

```
CREATE TABLE PERSON (
personid int identity (1,1) primary key not null,
personname varchar (255) not null,
age int
)
```

9. SUM:  SUM is a SQL aggregate function. that totals the values in a given column.
Syntax

```
SELECT SUM(Salary) AS TOTALSALARY FROM Salary
```

10. AVERAGE: AVG () computes the average of a set of values by dividing the sum of those values by the count of non-null values.
Syntax

```
SELECT AVG(Salary) AS AVERAGESALARY FROM Salary
```

11. COUNT:  The COUNT() function returns the number of records returned by a select query. Note: NULL values are not counted.
Syntax

```
SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE
```

12. MAX:  The MAX function in SQL is designed to identify the maximum value of a specified column. This function is particularly useful in retrieving the highest value from sets of data.
Syntax

```
SELECT MAX(column_1) FROM table.
```

13. MIN:  The MIN() function returns the smallest value of the selected column.
Syntax

```
SELECT MIN(column_1) FROM table.
```
# SQL CLAUSE
SQL Clauses are essential components of SQL that define how queries interact wit the database. They are used to specify condtions, modify data and control how results are returned. 

SQL Clause comprises of the folowing;
1. Group By Clause:  gorup rows that have the same value into summary row
 
 Syntax:

```
select count(staffid) state_of_origin from employee
GROUP BY state_of_origin
```
 
2. Having Clause:  enable user to filter the result based on the result

Syntax:

```
select count(staffid) state_of_origin 
from employee
GROUP BY state_of_origin 
HAVING COUNT(Staffid) >=3
```

3. Order By Clause:  to sort result either in ascending or descending order

  a. Ascending Order
  Syntax:

   ```
  select count(staffid) as staffperstate, state_of_origin 
  from employee
  GROUP BY state_of_origin
  order by count(staffid) asc
  ```

  b. Descending Order
  Syntax:

  ```
  select count(staffid) as staffperstate, state_of_origin 
  from employee
  GROUP BY state_of_origin
  order by count(staffid) desc
  ```

# COLUMN INDEX
Sorting by particular column by representing a number

Syntax:

```
select count(staffid) as staffperstate, state_of_origin 
from employee
GROUP BY state_of_origin
order by 2 desc
```

# COMPARISON/RELATIONAL OPERATORS

1. < =less then
Syntax

```
select * from Salary
where salary < 100560.934
```

2. < = greater than
Syntax:

```
select * from Salary
where salary > 100560.934
```

3. <> = not equal
Syntax:

```
select * from Salary
where salary <> 100560.934
```

# Range Operators  
Range operators are those operators which selects data according to particular range.
1. Between
   
Syntax:

```
select * from salary
where salary between 500000 and 900000
```

2. Not Between
   
Syntax:

```
select * from salary
where salary not between 500000 and 900000
```

# Logical Operator
Combine condition in a where clause to perform operation in a data e.g. AND, OR, NOT

- AND: if both conditions are true otherwise false

Syntax

```
SELECT * FROM EMPLOYEE
WHERE FIRSTNAME ='JOHNSON' AND GENDER= 'FEMALE'
```

- OR: either of the input

Syntax

```
SELECT * FROM EMPLOYEE
WHERE FIRSTNAME ='JUSTIN' OR GENDER= 'FEMALE'
```

- NOT: The NOT operator is used in combination with other operators to give the opposite result, also called the negative result.

Syntax

```
SELECT column1, colomn2, … 
FROM table_name WHERE NOT condition;
```
# UPDATE
The UPDATE statement in SQL is used to update the data of an existing table in the database.

Syntax:

```
UPDATE Salary
SET FIRSTNAME ='Emeka'
where staffid ='AB212'
```

# JOIN
A Join is used to combine rows or record from two or more table based on related columns between them
- Inner Join
- Left Join
- Right Join
- Full Join
[https://www.geeksforgeeks.org/sql-join-set-1-inner-left-right-and-full-joins/]

# UNION AND UNION ALL
UNION and UNION ALL in SQL are set operators that combine the results of two SELECT queries. Both share standard features, with one significant difference: UNION only returns a unique record, while UNION ALL returns all the records (including duplicates).

Union All

Syntax

```
	select * from LITA_Store_Lekki
	union all
	select * from LITA_Store_Marina
```

Union 

Syntax

```
select  customerID, Customer_gender, transaction_amount
from LITA_Store_Lekki
union 
select customerID, Customer_gender, transaction_amount
from LITA_Store_Marina
```

# SQL VIEWS
SQL views can streamline the data management processes and enhance the analytical capabilities. An SQL view is a virtual table that is created based on the result set of a SQL query. 

A view behaves like a SQL allowing you to select, update, insert, and delete data (with some limitation). A view is defined using a SELECT statement that can join multiple tables, filter rows and select specific columns. 

Syntax:

```
select * from [dbo].[vw_LITA_Store_Transaction_tbl]
```

# HOW TO EXPORT

1. Open Excel
2. Click on Data
3. Click on "from other source"
4. Click on "from SQR Server"
5. Data connect wizard

## POWERBI
PowerBI is a collection of software services, apps and connectors that work together to turn your unrelated sources of data into coherent, visually immersive and interactive insights.


# PowerBI - Interface 
![powerbi interface](https://github.com/user-attachments/assets/3a6faa8a-1d10-4f52-b562-c6be7b2f075e)
---
# PowerBI - Report View
![report view in powerbi](https://github.com/user-attachments/assets/bbd5b685-35c2-4995-a04e-a594be974d59)
---

## Data Sources for PowerBI
1. Excel
2. Cloud and Tables
3. SQL
4. Web

## Components of PowerBI
1. PowerBI Desktop: This is used to create reports and data visualization on data set
2. PowerBI Gateway: It allows you to query large datasets and benefit from the existing investment
3. PowerBI Mobile Apps: using PowerBI Mobile Apps, you can stay connected to their data from anywhere
4. PowerBI Service: This is a cloud service and is sued to publish PowerBI

## Data Sources
1.  Flat Files
2.  SQL Database
3.  OData Feed (Ordinary Database)
4.  Blank Query
5.  Azure Cloud Platfrom
6.  Online Services
7.  Blank Query

## Data Modelling
Data Modelling is one of the features used to connect multiples data sources using a relationship. A relationship defines how data sources are connected with eachother and you can create interesting data visualization on mulltiple data sources. 
- One-to-One
- One-to-Many
- Many-to-Many
Visualizations are used to efefctively present your data and are the basic building blocks of any business intelligence tool.

## Visualization Options
Step 1:  Define questions and goals
Step 2:  Collect Data
Step 3:  Data Wrangling
Step 4:  Determine Analysis
Step 5:  Interpret Results

## Data Analysis Expressions
DAX functions play an important roles in the usage of DAX for data modelling and reporting. DAX is a formula language and is a collection of functions, operators and constants that can be used in a formula or expression to calculate and return one or more values. 

## PRINCIPLES OF DATA VISUALIZATION
1.  Determine your audience
2.  Choose the right kind of chart to depict the type of information you have
3.  Focus on how your audience needs to use the data
4.  Provide the necessary context for data to be interpreted and acted upon appropriately
5.  Keep it simple
6.  Choose colors carefully to draw attention while also considering accessibility issues such as contrast
7.  Seek balance in your visual elements including text, color, shape etc
8.  Use Patterns
9.  Use proportion carefully so that differences in design size fairly represent differences in value 

# POWERBI FUNDAMENTAL
Power BI Fundamentals is for analysts looking to create professional, meaningful, and intuitive Power BI reports from a variety of data sources.

# GET DATA
- To connect to data, from the Home ribbon select Get data. 
- The Get Data window appears. 
- You can choose from the many different data sources to which Power BI Desktop can connect.

![lita class data](https://github.com/user-attachments/assets/7355826a-32e7-44c5-8739-9d3190611251)
---
## Transform Data
Transforming data helps clean and standardize it, ensuring accurate reporting and analysis.


![transform data](https://github.com/user-attachments/assets/f0220e88-f2e7-4255-83ea-1d363d0e6840)
---

## POWER QUERY FOR DATA TRANSFORMATION
Power Query is a data extraction, transformation, and loading (ETL) tool that comes bundled with Microsoft Excel, Power BI, and other Microsoft applications.

## APPENDING 
In Power Query, the Append operation creates a new query that contains all rows from a first query followed by all rows from a second query.

---
![APPENDING DATA](https://github.com/user-attachments/assets/590800b5-2e9d-4894-b903-896131333b83)
---

## APPENDING MORE THAN ONE TABLE
Appending: to join two table together to continue from where the last table stopped.
Note: Appending data must have the same schema (attribute).

---
![APPENDING THREE TABLE](https://github.com/user-attachments/assets/bd784c5f-d072-45b4-aed9-ad2c2be052bd)
---

# MERGING
 A merge queries operation joins two existing tables together based on matching values from one or multiple columns

![MERGE](https://github.com/user-attachments/assets/ae6b240d-3e26-4fb3-bbc4-eb212f1b648d)
---

# Merged Table

![MERGED TABLE](https://github.com/user-attachments/assets/b24545af-c6b2-49ce-a373-b0a983291c59)
---

Syntax

```
= Table.NestedJoin(#"May Deposit", {"Date "}, #"May Loan", {"Date "}, "May Loan", JoinKind.LeftOuter)
```

## ExpandTable
Retrieves a context with added levels of detail compared to the current context. 

![expanded](https://github.com/user-attachments/assets/ea6e286b-32d6-4e70-9f41-6650e96c0aa4)
---

Syntax
```
= Table.ExpandTableColumn(Source, "May Loan", {"Loan Balances"}, {"May Loan.Loan Balances"})
```

# Parser
A SQL parser is a tool that reads SQL code and converts it into a format that can be understood and processed by a computer.

![parse](https://github.com/user-attachments/assets/cb476178-46dd-4bad-9130-6482a126faa2)

# Date Function
The DATE() function extracts the date part from a datetime expression. 

![date table](https://github.com/user-attachments/assets/34177e13-2ace-4e9b-879b-413625c06cfe)

# OUSTANDING COLUMN TABLE

![oustanding table](https://github.com/user-attachments/assets/a8016d56-5fca-49db-a383-e7d5f09f6522)

Syntax:

```
= Table.AddColumn(#"Renamed Columns", "Oustanding", each [May Loan Summary] - [Loan Deposit])
```

# Column Quality
In Power BI, column quality is a feature that displays the percentage of valid, empty, and error entries in a column:
Valid: Green
Error: Red
Empty: Dark gray
Unknown: Dashed green
Unexpected error: Dashed red 
To enable column quality, you can:
Go to the View tab
Select Column Quality 

![Capture](https://github.com/user-attachments/assets/4633b936-21a2-4941-99cd-6d1adcb882e2)


14TH OCTOBER, 2024

## MY LITA CLASS PROJECT

# Project 1: Sales Performance Analysis for a Retail Store 
Summary: In this project, you are tasked with analyzing the sales performance of a retail store. 
You will need to explore sales data to uncover key insights such as top-selling products, regional 
performance, and monthly sales trends. The goal is to produce an interactive Power BI 
dashboard that highlights these findings.


# Create any other interesting report
Conditional Functions	-	IF Function

```
=IF(G2<=10, "Low", IF(G2<=50,"Medium","High"))
```

![IF](https://github.com/user-attachments/assets/281ebbe7-ee23-4e7c-84e9-c2e2aafc1602)


# VISUALIZATION

![class project](https://github.com/user-attachments/assets/c62b7ab7-419f-40d4-8308-82fb849c7535)

## Sort by Column

Sort by Column feature allows you to control the order in which data is displayed in visualizations by using a custom sorting column


![sort by](https://github.com/user-attachments/assets/92d98e76-1ad0-41ab-8719-82832b3b5c0b)


