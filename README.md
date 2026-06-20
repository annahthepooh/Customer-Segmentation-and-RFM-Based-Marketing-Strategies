# Customer Segmentation & RFM Based Marketing Strategy

## Problem Statement
* This project analyzes customer data to group them into segments based on purchasing behavior and recommend data driven retention strategies.

## Executive Summary
* In this project, **customer segmentation** is conducted using a **Recency, Frequency and Monetary(RFM) framework** on an Auto Sales Dataset using **EXCEL** based on purchasing behavior and value contribution. The goal is to identify high value, at-risk and inactive customers to help the business to **increase Conversion Rate** and **reduce Churn Rate** . The analysis reveals distinct customer segments and shows the **risk of churn** to be **74.33%** and the **Average Order Value** to be unexpectedly high at **$3.55K**

## 🛠 Tools & Skills Demonstrated
<details>
### Excel
- Data cleaning and validation
- RFM Metric Calculation
- Customer Analysis
- Customer Aggregation
- Segmentation Modeling

<summary><b>Click here to expand the section</b></summary>

### Power BI
- Dashboard Design
- Data Visualization
- KPI Presentation

### Marketing Analytics
- RFM Analysis
- Customer Segmentation
- Customer Lifetime Value Analysis
- Churn Risk Identification

### Business Skills
- Customer Retention Strategy
- Marketing Strategy Development
- Revenue Optimization
- Business Recommendations
</details>

## The Workflow
* ### Data Cleaning & Preparation (EXCEL)
* Used the **first rows as headers**
* **Standaridized the columns** by checking for NULL and blank spaces
* **Changed the datatypes** of the columns and **renamed the columns** to be legible

### Data Manipulation (EXCEL)
* Calculated the **Total Sales per Customer** and **Total Orders per Customer** using the **VLOOKUP** function
* Used the **Percentile INC** function to calculate the **Recency**, **Frequency** & **Monetary Cutoffs**
* Calculated the **R**,**F** & **M Scores** using the **Match** function and concatenated them to get the **RFM Codes** used for segmentation
* Segmented the customers using the **IFS statement** and assigned **stategies** using the **VLOOKUP** function

### Data Visualization (Power BI)
* This is a link to the Power BI dashboard: 

## Key Insights
* The **Champions** make up the largest percent of the total customer base(**36.99%**), followed by **Loyalists** who make up **32.63%**. The 2 segments make up almost **70%** of the whole customer base which shows that the business has an exceptionally healthy core.
* The **At Risk** customers(**337**) and the **Standard** customers(**991**) have a massive presence and the **percentage Churn Risk** is alarmingly high(**74.33%**) showing that the customer base is at a high risk of dropping as much as the business is healthy.
* The business relies on a few **Whale** customers who make orders of massive volume shooting the Average Order Value to $3.55K which is distorted.

## Final Recommendations
* Implement **VIP Loyalty Program** for **champions** to strengthen engagement and increase long term retention because this segement represents the highest value customers.
* Introduce targeted upselling strategies to **Loyalists** by promoting premium product values to maximize customer lifetime value.
* Deploy an **automated Re-engagement campaign** specifically for the **At risk** customers(337) to prevent churn leveraging personalized offers and reminders based on their recent activity patterns.
* Assign **seperate dedicated account management** to **high frequency**, **high monetary value** customers(The '**Whales**') to ensure personalized service, improve satisfaction and reduce risk of high impact churn.
