Bike Sales Data Analysis with Excel Pivot Tables
This repository contains materials for a lab exercise focused on analyzing bicycle sales data using Microsoft Excel Pivot Tables and Charts. The project aims to identify purchasing patterns across different demographic groups and geographical locations to inform marketing strategies.
Table of Contents
Project Overview
Objectives
Data Source
Key Findings
How to Use (Lab Instructions Summary)
Screenshot
Future Improvements
Project Overview
This project demonstrates the power of Excel Pivot Tables and Charts for data summarization, analysis, exploration, and presentation. By reorganizing raw sales data, we can uncover non-obvious trends and make informed business decisions. The "pivot" functionality allows for viewing data from various perspectives without altering the original dataset.
The primary goal is to help a bicycle sales company understand customer purchasing behavior to:
Determine where marketing efforts need to be concentrated to reach under-represented demographic groups.
Identify differences in purchasing patterns between the countries where the company operates.
Objectives
Upon completing this lab, you will have learned the basics of:
Creating a pivot table in Microsoft Excel.
Summarizing, analyzing, exploring, and presenting data using pivot tables.
Adding visualizations (charts) to pivot table data to analyze trends and comparisons.
Data Source
The analysis is based on a bicycle sales dataset provided in an Excel file. This file includes fields such as Year, Age Group, Customer Gender, Country, and Order Quantity, among others.
Excel Data File: Day_3_Task_1_Bike_Sales_Pivot_Lab.xlsx (Please note: This file is expected to be part of the repository, but is not directly provided in this README content. It is mentioned in the lab document.)
Key Findings
Through the pivot table and chart analysis, several insights were gained:
Youth age group: Globally, this demographic shows the poorest sales performance.
Female Adults: This group is purchasing the most product.
Geographical Variations:
Sales are present in Australia across all categories except male youth.
No sales were observed for adult males in France.
The United Kingdom has only one successful market category.
These findings prompt further questions for the company to develop targeted business decisions.
How to Use (Lab Instructions Summary)
This repository accompanies a lab document, Day_3_Task_1_Bike_Sales_Pivot_Lab.pdf, which provides detailed step-by-step instructions. Below is a high-level summary:
Part 1: Creating an Excel Pivot Table
Download and Open Data: Open the Day_3_Task_1_Bike_Sales_Pivot_Lab.xlsx file in Microsoft 365 Excel online.
Create Pivot Table: Go to Insert menu tab, select Pivot Table, and choose New Worksheet.
Select Fields: In the PivotTable Fields dialog, select Year, Age Group, Country, and Order Quantity.
Refine Table:
Remove Year from the pivot table fields as its sum is meaningless in this context.
Collapse/expand age groups to view aggregated or detailed country data.
Drag Country to the Columns pane for a different data view.
Fill blank cells with 0 (zero) via Pivot Table -> Settings -> For empty cells show.
Centre numeric columns for readability.
Sort Age_Group from Youth to Adults (Sort Descending).
Add Gender: Include Customer_Gender to the pivot table for more granular analysis.
Part 2: Visualising Pivot Table Data
Create Chart: Select all cells in the pivot table, go to Insert, and select the Stacked Column chart type.
Format Chart:
Resize and move the chart for clarity.
Right-click the chart, select Format, and change the Chart Title to "Sales Summary."
Analyse Chart Data: Use the visual representation to identify trends and disparities in sales across demographics and countries.
Revise Chart Format: Collapse gender information in the pivot table to show aggregated sales data per age group for each country, updating the chart dynamically.
Screenshot
Below is a screenshot of the Excel worksheet showing the raw data and a sample of the pivot table setup.
Future Improvements
More Granular Analysis: Explore other dimensions like Product Category or Sub-Category.
Advanced Visualizations: Use more sophisticated charting tools or dashboards to create interactive reports.
Predictive Analytics: Apply statistical methods to forecast sales trends based on historical data.
Automated Reporting: Explore ways to automate the data refreshing and report generation process.
Marketing Action Plan: Develop a concrete marketing action plan based on the identified under-represented groups and regions.
