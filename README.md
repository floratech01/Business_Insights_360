# Business_Insights_360

Welcome to the Business Insights 360 Power BI project repository! 🚀
# Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

## Live Dashboard

Explore the live dashboard [here](https://app.powerbi.com/groups/me/apps/332ee471-0da6-4173-af0e-fc1259f22e60/reports/e8ce437e-6ad5-4758-87fe-4bf03d811072/ReportSection306262a00c6089dc14c0?experience=power-bi).

# Tech stacks
---
+ SQL
+ PowerBi Desktop
+ Excel
+ DAX language
+ DAX studio (for optimizing the report)
+ Project charter file
  
# Features
---
+ Finance View: Detailed financial analysis, including revenue, expenses, and profit margins. Analyzed crucial KPI indicators such as Net Sales, Gross Margin %, and Net Profit %. Created a comprehensive P & L Statement with YOY growth.
+ Sales View: Insights into product and customer performance. Explored Customer Performance based on Net Sales and Gross Margin.
+ Marketing View: Enhanced Marketing insights with segment performance and Net Profit metrics.
+ Supply Chain View: Optimization metrics for efficient supply chain management. Surveyed the variance of Actual Sales and Forecast accuracy.
+ Executive View: Metrics critical for top-level decision-makers. Examined Yearly Trends by Revenue, GM %, NP % & Market Share %. Listed the TOP 5 Customers & Products by Revenue Contribution.

# PowerBI techniques Learnt 
---
+ What are all the questions should be asked before starting the project
+ Creating calculated columns
+ creating measure using DAX language
+ Data modeling
+ Using Bookmarks to switch between two visuals
+ Page navigation with buttons
+ Using divide function to prevent zero division errors
+ creating date table using m language
+ Dynamic titles based on the applied filters
+ Using KPI indicators
+ Conditional formatting the values in visuals using icons or background color
+ Data validation techniques
+ PowerBi services
+ Publishing reports to PowerBi services
+ Setting up personal gateway to set up the auto refresh of data
+ PowerBi App creation
+ Collaboration, workspace, access permissions in PowerBi services
And more 😅

# Business related terms
---
+ Gross price
+ Pre-invoice deductions
+ Post-Invoice deductions
+ Net Invoice sale
+ Gross Margin
+ Net sales
+ Net profit
+ COGC - cost of goods sold
+ YTD - Year to Date
+ YTG - Year to Go
+ Direct
+ Retailer
+ Distributors
+ Consumer

# Company’s back ground
---
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

+ Retailers
+ Direct
+ Distributors
Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project

# Questions to ask before starting with dashboard  
---
+ What is the objective of building this PowerBi dashboard?
+ In what terms the success of this project will be measured?
+ What will be time dead-line of the project?
+ do the stakeholders expecting pre-view before the actual release?
+ What are all the hopes stakeholders have out of this project?
+ what are all fears the stakeholder have in terms of building this dashboard?
+ Who are all will be using this dashboard and for what purpose?
+ what are all expectation the stakeholders have, by the completion of this project?
+ What can go wrong while building this project?
+ what are all the resources/ data needed to build this dashboard?
+ is there any inputs from stakeholders in terms of design and views of the dashboard?
After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

# Dataset Understanding.
---
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products
Fact table : It will have the data about the transactions

+ gdb041:
  - dim_customer
    * 27 distinct markets (ex India, USA, spain)
    + 75 distinct customers thorough out the market
    + 2 types of platforms
      - Brick & Motors - Physical/offline store
      * E-commerce - Online Store (Amazon, flipkart)
    + Three channels
Retailer
Direct
Distributors

Fact table : It will have the data about the transactions
