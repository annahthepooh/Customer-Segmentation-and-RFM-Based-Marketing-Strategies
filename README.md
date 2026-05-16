# Auto-Dataset-RFM-Analysis

## Executive Summary
* In this project, I conducted **customer segmentation** using a **Recency, Frequency and Monetary(RFM) framework** on an Auto Sales Dataset using **EXCEL**. The goal was to group customers based on their purchasing behavior to help the business to **increase Conversion Rate** and **reduce Churn Rate** . I manipulated the dataset to come up with **Days Since Last Order**, **Total Sales** and **Number of Orders Made** as metrics which I used to discover that the **risk of churn** is **74.33%** and the **Average Order Value** is unexpectedly high at **$3.55K**

## The Workflow
* ### Data Cleaning & Preparation (EXCEL)
* Used the **first rows as headers**
* **Standaridized the columns** by checking for NULL and blank spaces
* **Changed the datatypes** of the columns and **renamed the columns** to be legible

* ### Data Manipulation (EXCEL)
* Calculated the **Total Sales per Customer** and **Total Orders per Customer** using the **VLOOKUP** function
* Used the **Percentile INC** function to calculate the **Recency**, **Frequency** & **Monetary Cutoffs**
* Calculated the **R**,**F** & **M Scores** using the **Match** function and concatenated them to get the **RFM Codes** used for segmentation
* Segmented the customers using the **IFS statement** and assigned **stategies** using the **VLOOKUP** function

## Business Questions
* **Days Since Last Order** - How recent is each customer's last purchase?
* **Total spend per Customer** - How much does each customer spend on orders?
* **Total Number of Orders per Customer** - How many orders does each customer make?

## Key Insights
* The **Champions** make up the largest percent of the total customer base(**36.99%**), followed by **Loyalists** who make up **32.63%**. The 2 segments make up almost **70%** of the whole customer base which shows that the business has an exceptionally healthy core.
* The **At Risk** customers(**337**) and the **Standard** customers(**991**) have a massive presence and the **percentage Churn Risk** is alarmingly high(**74.33%**) showing that the customer base is at a high risk of dropping as much as the business is healthy.
* The business relies on a few **Whale** customers who make orders of massive volume shooting the Average Order Value to $3.55K which is distorted.

## Final Recommendations
* Offer **Champions** **VIP Recognition** and **inclusivity** to retain them as important customers.
* **Upsell Premium Auto packages and accessories* to **Loyalists** maximize their high lifetime value.
* Implement an **automated Re-engagement campaign** specifically for the **At risk** customers(337) because they already show an excellent Frecency score to prevent them from slipping into the hibernating funnel.
* Exercise **seperate dedicated account management** for the customers with **high frequency** and **high monetary scores**(The '**Whales**') to ensure tracking of the customer experience and avoid potential churn which can heavily affect the business health.