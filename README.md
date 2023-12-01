# Data Analyst Project – Sales Management

## Business Request & User Stories

The business request for this data analyst project aimed to create an executive sales report for sales managers. The following user stories were defined to fulfill delivery and ensure the acceptance criteria were maintained throughout the project:

| # | As a (role)              | I want (request / demand)                            | So that I (user value)                                      | Acceptance Criteria                           |
|---|--------------------------|------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------|
| 1 | Sales Manager            | To get a dashboard overview of internet sales        | Can follow better which customers and products sell the best | A Power BI dashboard updating data once a day |
| 2 | Sales Representative     | A detailed overview of Internet Sales per Customers  | Can follow up my customers that buy the most                | A Power BI dashboard allowing data filtering for each customer |
| 3 | Sales Representative     | A detailed overview of Internet Sales per Products   | Can follow up my Products that sell the most               | A Power BI dashboard allowing data filtering for each product |
| 4 | Sales Manager            | A dashboard overview of internet sales               | Follow sales over time against budget                       | A Power BI dashboard with graphs and KPIs comparing against budget |

## Data Cleansing & Transformation (SQL)

To create the necessary data model for analysis and meet the business needs from the user stories, the following tables were extracted using SQL. 

(Refer to the SQL statements in the actual repository)

## Data Model

Below is a screenshot of the data model after cleansing and preparing tables, which were read into Power BI.

![Data Model Screenshot](https://1drv.ms/i/s!Ag0dOGcIynRK5AjinWUkClmNF66E?e=LqRalJ)

This data model demonstrates how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

## Sales Management Dashboard

The finished sales management dashboard comprises one page acting as a dashboard and overview, with two other pages focusing on combining tables for necessary details and visualizations to display sales over time, per customers, and per products.

Click the picture to open the dashboard and try it out!

![Sales Management Dashboard](https://1drv.ms/i/s!Ag0dOGcIynRK5Al4qqptph7DG3fi?e=TOdkdp)
