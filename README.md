# Customer-Churn-Analysis
An interactive Power BI dashboard project that analyzes customer churn trends, customer demographics, contract types, billing behavior, and service usage to identify high-risk customers and improve retention strategies.

📌 Project Overview

This project presents an interactive Customer Churn Analysis Dashboard developed using Microsoft Power BI.
The dashboard analyzes customer churn behavior, customer demographics, internet services, payment methods, contract types, and customer retention patterns using interactive visualizations, KPIs, slicers, and DAX measures.

The project helps businesses identify high-risk customers, understand the major factors influencing churn, and improve customer retention strategies through data-driven insights.

#  Objectives
Analyze customer churn patterns and customer behavior
Identify high-risk customers likely to churn
Compare churn based on:
Gender
Contract type
Internet service
Senior citizen status
Payment methods
Visualize customer retention trends
Provide business insights for improving customer satisfaction and retention

Tools & Technologies Used
Microsoft Power BI
DAX (Data Analysis Expressions)
Power Query
Data Visualization
KPI Cards
Interactive Filters & Slicers
📂 Dataset Information

The dataset contains customer information such as:

Customer ID
Gender
Senior Citizen
Contract Type
Internet Service
Phone Service
Monthly Charges
Tenure
Payment Method
Churn Status
# 📊 Dashboard Features
1. KPI Cards

Displays:

Total Customers
Churned Customers
Churn Rate
Average Monthly Charges
Average Tenure
2. Gender-Wise Customer Analysis
Customer distribution by gender
Gender-based churn insights
Customer comparison between male and female customers
3. Contract Type Analysis

Analyzes churn behavior across:

Month-to-month
One year
Two year contracts
Insight

Customers with month-to-month contracts show higher churn rates.

4. Internet Service Analysis

Compares customer churn among:

Fiber optic
DSL
No internet service
Insight

Fiber optic customers show higher churn rates compared to other service users.

5. Payment Method Analysis

Analyzes churn behavior by payment methods:

Electronic check
Mailed check
Bank transfer
Credit card
Insight

Electronic check users have the highest churn count.

6. Tenure Analysis
Customer distribution by tenure groups
Monthly charges by tenure
Customer loyalty analysis
Insight

Long-term customers are more likely to stay with the company.

7. Senior Citizen Analysis

Compares churn behavior between:

Senior citizens
Non-senior citizens

# DAX Measures Used
Churn Rate Measure
Churn Rate =
DIVIDE(
    CALCULATE(
        COUNTROWS(CustomerData),
        CustomerData[Churn] = "Yes"
    ),
    COUNTROWS(CustomerData)
)
#  Key Insights
Month-to-month contract customers have higher churn.
Fiber optic users show higher churn percentages.
Electronic check users are more likely to churn.
Customers with longer tenure are more loyal.
Interactive dashboards help identify customer retention opportunities.
📷 Dashboard Visualizations

The dashboard includes:

KPI Cards
Donut Charts
Bar Charts
Column Charts
Line Charts
Scatter Plots
Treemaps
Stacked Bar Charts
Interactive Slicers
# Business Impact

This dashboard helps businesses:

Improve customer retention strategies
Identify high-risk customers
Reduce customer churn
Make data-driven business decisions
Improve customer satisfaction
