# LITA_Project

## Project Title: Sales Report and Analysis

### Project Overview
This Data Analysis project aims to generate insight into the sales performance of each region,market,model,store, and line of business over the past 3 years. By analysing the various parameters in the data received, we seek to gather enoung insight to make reasonable decision and to know the best performance from our data.

### Data Sources
The primary source of Data used here is Data Sales.csv and this is an open source data that can be downloaded from an open source online.

### Tools Used
- Microsoft Excel
    1. For Data Cleaning
    2. For Data Analysis
    3. For Data Visualization
       
- SQL - Structured Query Language for Quering of Data
- Github for Portfolio Building

### Data Cleaning and Preparation
In the initial phase of the data cleaning and preparations, we perform the foolowing action;
1. Data loading and Inspection
2. Handling missing variables
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved the exploring of the data to answer some questions about the data such as;
- What is the overall revenue for the each region
- What are the models on peak sales?
- Which store has the lowest unit sold

###  Data Analysis
Here we include some basic lines of code or queries used during our analysis;

```SQL
SELECT region sum(profit)
as TotalProfit from Table1
```
