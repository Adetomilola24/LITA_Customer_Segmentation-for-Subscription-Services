# LITA_Customer_Segmentation-for-Subscription-Services
This project involves analysing customer data for a subscription service to identify segments and trends. and identify key trends in cancellations and renewals. 

## Project Title: Customer Segmentation for Subscription Services
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Data Tools Used](#data-tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

## Project Overview
In this project, 
- We analyze customer data for a subscription service to understand user behavior
- Subscription patterns
- Trends in cancellations and renewals.
  
By identifying distinct customer segments, our goal is to highlight key factors influencing subscription durations, churn rates, and popular subscription types. This analysis will culminate in a Power BI dashboard, providing visual insights into customer demographics, subscription trends, and churn predictors.

## Data Sources
The data for this project includes:

1. Customer Information: Basic demographic and regional details, subscription dates, and customer IDs.
2. Subscription Data: Details about subscription types, durations, renewal history, and cancellation timestamps.

## Data Tools Used
The following tools were utilized to explore, clean, analyze, and visualize the data:

1. Microsoft Excel: For initial data exploration and pivot table analysis.
2. SQL: To run specific queries and extract insights from the database.
3. Power BI: For creating an interactive dashboard that visualizes customer segmentation, subscription trends, and key metrics.

## Data Cleaning and Preparation
The data cleaning and preparation process involved:

1. Missing Value Analysis: Checking for any missing values in crucial fields, especially for subscription dates and customer demographics.
2. Data Consistency Checks: Verifying consistent formatting for dates, regional codes, and subscription type fields.
3. Feature Engineering: Creating calculated fields like subscription duration (e.g., months), churn indicators, and categories based on subscription types (e.g., basic, premium).

## Exploratory Data Analysis
For exploratory data analysis, pivot tables and descriptive statistics helped in identifying trends such as:
1. Subscription Types: Understanding which subscription types are most popular among different demographics.
2. Churn Rate Trends: Analyzing patterns in subscription cancellations over different periods.
3. Subscription Duration: Calculating average subscription duration and identifying customer characteristics associated with longer or shorter durations.

## Data Analysis
Data analysis was conducted in SQL, focusing on specific insights as outlined below:

1. Customer Count by Region: To observe customer distribution across regions.
2. Most Popular Subscription Types: Analyzing which types are most chosen by customers.
3. Churn Insights: Identifying customers who canceled within the first six months and factors influencing early cancellation.
4. Average Subscription Duration: Calculating the mean duration across customer segments.
5. Long-Term Subscribers: Identifying customers with subscriptions over 12 months to assess long-term engagement.
6. Revenue by Subscription Type: Determining revenue contributions by different subscription types.
7. Churn by Region: Highlighting the top regions with the highest subscription cancellations.

## Data Visualization
The Power BI dashboard provides interactive visuals to communicate the analysis insights:

1. Customer Segmentation View: Segments customers based on subscription type, duration, and regional distribution.
2. Churn Analysis: Visualizes trends in cancellations over time and highlights regions with the highest churn.
3. Subscription Trends: Shows the most popular subscription types and patterns in renewals and cancellations.
4. Slicers and Filters: Interactive slicers allow filtering by subscription types, duration, and regions, providing a deeper dive into specific customer segments.
