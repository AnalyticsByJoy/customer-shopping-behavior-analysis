# customer-shopping-behavior-analysis

## Table Of Contents
[Projecy Overview](#project-overview)




## Project Overview
This project analyzes customer shopping behavior to uncover insights into sales performance, product effectiveness, and customer engagement patterns.

Using Microsoft Power BI, the dashboard explores purchasing trends across 3,900 transactions, focusing on how product categories, customer demographics, and subscription behavior influence overall revenue.

The analysis highlights several important patterns including revenue concentration risks, subscription underperformance, gender imbalance in spending, and opportunities to improve customer retention and product diversification.

### Business Objectives

The analysis aims to answer key business questions:
	1.	What factors drive total revenue?
	2.	Which product categories and items perform best?
	3.	How do customer demographics influence purchasing behavior?
	4.	How effective is the subscription model?
	5.	Where are the main growth opportunities?

### Dataset Overview

The dataset contains 3,900 transaction records with 16 attributes, including:

###### Customer Demographics
- Age
- Gender
- Location

###### Purchase Information
- Product Category
- Item Purchased
- Size
- Season

###### Financial Metrics
- Purchase Amount

###### Engagement Indicators
- Subscription Status
- Previous Purchases
- Review Rating

### Data Preparation

#### Data Loading

The raw dataset was imported into Power BI Desktop, and column structures were verified to ensure correct data types.

#### Data Cleaning (Power Query)
- Checked for missing values and blank rows (none detected)
- Verified data consistency across fields
- Prepared data for modeling and visualization

 #### Data Modeling

Several calculated measures and KPIs were created using DAX to support deeper analysis:
- Total Revenue
- Total Customers
- Revenue Percentage
- Average Review Rating
- Average Purchase Value
- Average Previous Purchases
- Number of Unique Items
- Repeat Customer Percentage
- Age Group Column

These metrics formed the backbone of the analytical dashboard.

###  Dashboard Design

The Power BI dashboard was designed to provide clear, interactive business insights.

Features included
- KPI cards for high-level performance tracking
- Interactive slicers for:
- Gender
- Season
- Location
- Purchase Frequency
- Visualizations including:
- Column charts
- Bar charts
- Pie charts
- Donut charts
- Text insight boxes

### Project Insights

