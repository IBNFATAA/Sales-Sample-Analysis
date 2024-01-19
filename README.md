# Sales Sample Analysis

![Sales_Grocery (1)](https://github.com/habeebsalaudeen/Sales-Sample-Analysis/assets/97491265/55a6ee42-4155-45f7-af9d-1fc626c24a6b) | ![groc_store](https://github.com/habeebsalaudeen/Sales-Sample-Analysis/assets/97491265/1f3f188a-cb9c-4d0e-a974-eb8af42f2cb0)


## Introduction
This is a Power BI on sales analysis of an imaginary company called **Sales Sample**.
The project is to analyze and derive insights to answer crucial questions and help the company make data driven 
decisions.
**_Disclaimer_** : All datasets and reports do not represent any company, institution or country, but just a 
dummy datasets to demonstrate capabilities of Power BI.

## Problem Statement
1. Sum of sales by year, month and ship mode. 
2. Top 5 Sum of sales by city and Bottom 5 Sum of sales by city.
3. Profit  by year, month and ship mode.
4. Top 5 profit by city and Bottom 5 profit by city

## Skills / Concepts Demonstrated
- Data Modeling and Relationships
- DAX (Data Analysis Expressions)
- Aggregation Techniques
- Filters and Slicers
- Buttons

## Modelling
In constructing our sales analysis model in Power BI, I took a hands-on approach, personally deriving and connecting 
various components to ensure a comprehensive and tailored solution. 

![Model](https://github.com/habeebsalaudeen/Sales-Sample-Analysis/assets/97491265/7850110f-a587-48f4-a7ce-a1609219b3de)

The model is a star schema.
There are 4 dimension tables and 1 fact table. The dimension are all joined to the fact table with a one-to-many relationship.

## Visualization:

The report comprises 2 pages:
1. Sales report 1
2. Sales report 2

You can interact with the report {here} 
(https://app.powerbi.com/groups/me/reports/8fe96508-708d-4aea-8604-4c0ece7cabb9/ReportSection62295d81cb28006e7dcb?experience=power-bi)

### Sales report
In this Power BI sales analysis, I skillfully crafted a dynamic and comprehensive model. I implemented advanced measures, creating slicers for both month and segments to ensure seamless interaction with the report, line chart illustrate the sum of sales over months and years, allowing users to grasp sales trends without interference from slicers. Additionally, a doughnut chart visualizes sales distribution by ship mode. To highlight key categories, a stacked bar chart showcases the top 5 and bottom 5 sales, contributing to a comprehensive and interactive exploration of sales insights. The report seamlessly combines interactivity with user-friendly design, enabling stakeholders to make informed decisions and strategize effectively based on the presented data.
![Sales (1)](https://github.com/habeebsalaudeen/Sales-Sample-Analysis/assets/97491265/54493a37-a3f8-41f6-af64-0e5d846fd5c7)


### Profit report
This Power BI report provides a detailed analysis of profit data with dynamic features such as buttons and slicers for month and segment selection. The primary focus is on a line chart illustrating the sum of sales over months and years, allowing users to grasp profits trends without interference from slicers. Additionally, a doughnut chart visualizes profit distribution by ship mode. To highlight key categories, a stacked bar chart showcases the top 5 and bottom 5 sales, contributing to a comprehensive and interactive exploration of tremendous insights when it comes to profit. The report seamlessly combines interactivity with user-friendly design, enabling stakeholders to make informed decisions and strategize effectively based on the presented data.
![Profit](https://github.com/habeebsalaudeen/Sales-Sample-Analysis/assets/97491265/3e83b7c2-4152-4f9e-a2bc-c25ff7b58f9a)


## Conclusion and Recommendation
The insights generated from the report shows:
- The highest generated sales by Month and year = (NOVEMBER)
- Highest sales by ship mode = (STANDARD CLASS)
- Highest sales by CITY = (NEW YORK)
- Worst sales by city = (Waco)
- The highest generated profit by Month and year = (OCTOBER)
- Highest profit by profit = (STANDARD CLASS)
- Highest profit by profit = (NEW YORK)
- Worst sales by profit = (ELYRIA)
