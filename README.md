# Subscriber Intelligence: Churn & Revenue Analysis Dashboard (power bi project)

An interactive Power BI dashboard built to uncover patterns in subscriber churn, revenue generation, and risk segmentation. The dashboard helps stakeholders identify high-risk users, optimize pricing strategies, and improve customer retention.

## 1. Purpose

The Subscriber Intelligence Dashboard is designed to provide insights into why subscribers leave, how revenue is distributed across demographics, and where churn risk is highest. This Power BI report supports business leaders, data analysts, and subscription strategists in making data-driven decisions to reduce churn and increase customer lifetime value


## 2.  Tech Stack

   ⚪ Power BI Desktop – for dashboard creation and interaction

   ⚪ DAX – used for calculated KPIs like churn rate, MRR, ARR, and churn risk

   ⚪ Power Query – for transforming and cleaning the dataset

   ⚪ Excel – used for data preprocessing and initial cleanup

   ⚪ File Format – .pbix for dashboard, .csv for raw data, .png for screenshots


## 3. Data Source

**source:** `Subscription_Service_Churn_Dataset.csv'(kaggle)

Contains details about:

- Subscription types
- Monthly charges
- Devices used
- Customer demographics (gender, age, payment method)
- Account age, churn status, and user ratings

## 4.  Highlights

### Business Problem

Subscription services face difficulty identifying why users churn, where revenue dips, and which customer groups need attention.

- What plan or payment method has higher churn?
- Who are the high-risk subscribers?
- What are the key revenue drivers?


### 5. Goal of the Dashboard

To create an insightful dashboard that:

- Tracks and visualizes churn KPIs
  
- Highlights revenue and customer behavior
  
- Pinpoints high-risk users for targeted retention
  

##  6. Key Visuals


- Churn Rate KPI – Overall percentage of customers who left

- ARR / MRR Cards – Annual and Monthly Recurring Revenue

- Churn by Subscription Type – Bar chart showing churn count by plan

- Churn by Device – Donut chart showing device type breakdown

- Churn by Gender – Pie chart comparing churn across genders

- Avg Monthly Charges by Plan – Line chart comparing pricing

- Churn by Payment Method – Bar chart showing churn behavior by payment type

- Revenue by Account Age – Combined bar showing charge and age relationship

- Customer Churn Risk Table – Sorted table highlighting top high-risk customers
  

## 7.  Business  impact & Insights


- Premium plan users with shorter account age are at the highest churn risk, suggesting a need for early-stage engagement strategies.
  
- Electronic payment method users show higher churn, indicating a possible issue with ease of transaction or perceived security.
  
- Targeted retention strategies can be applied by segmenting based on gender, device type, and plan usage.
  
- High-revenue customers with low tenure should be prioritized for loyalty programs to maximize lifetime value.
  
- Churn is lowest among long-term subscribers on standard plans, highlighting the success of stable mid-tier pricing.
  
- Tablet and TV device users show lower churn, suggesting those platforms may offer a better user experience.
  
- Customers with lower monthly charges churn less frequently, indicating that affordability may reduce drop-off.
  
- Lack of engagement (e.g., account inactivity) correlates with increased churn — engagement metrics can improve retention modeling.
  
- High rating customers churn less, implying that satisfaction surveys could serve as early churn predictors.
  
- ARPU (Average Revenue per User) remains stable across age groups, showing that pricing strategy is well-distributed but could be better optimized by tenure.



## 8. Dashboard Preview

![Subscriber Churn Dashboard](https://github.com/iamsunaina1/subscriber-intelligence-dashboard/blob/main/snapshot%20of%20the%20dashboard.png)



