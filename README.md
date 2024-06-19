# Wixsin Company Revenue Analysis

## Introduction
The goal of this project is to analyze sales data in order to find trends, patterns, and KPIs that can be used to inform business decisions. An interactive Excel dashboard presents and visualizes the analysis results for simple exploration and comprehension.

**_Disclaimer_**: _All datasets and reports are fictitious and are intended only to show off Microsoft Excel's capabilities. They do not represent any organization, nation, or enterprise._

## Problem Statement
1. Is revenue growing on a monthly basis?
2. What days of the week does the company make the most revenue?
3. What is the proportion of category to total revenue?
4. What is the contribution of each state to the total revenue of the company?
5. What segment has the highest amount of revenue?
6. What are the top 5 selling products?

## Skills Demonstrated
The Following Microsoft Excel features were incorporated:
- Data Cleaning
- Data Consolidation with Index match
- Data Modelling with Power Pivot
- Pivot
- Visualisation chats
- Slicer

## Data Sourcing 
This revenue dataset was generated online and saved as a CSV file. The four sheets that make up the dataset are titled Location, Manufacturer, Sales, and Products. contains details on sales transactions, including dates, goods, amounts, costs, and client information. To do insightful analysis, one must be aware of the dataset's structure.

## Data Transaformation 
After loading the dataset into Ms. Excel, the dataset was inspected. In order to utilize Pivot, the Excel spreadsheet's four separate spreadsheets or tables have to be combined into a single table using Index Match. A table named sales_table was created from the spreadsheet's structure. Certain columns, like Month and Week, which I developed but extracted from the Date column, were not included in the spreadsheet. The dataset comprises 1412 rows and 14 columns, with a total revenue of $9,826,183 and 1430 total units.
Nevertheless, adopting Power Pivot—which eliminates the requirement for data consolidation—was also significantly faster. I was able to jump right into pivot and analysis using Power Pivot and data modeling. 
