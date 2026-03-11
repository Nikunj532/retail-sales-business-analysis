# Retail Sales Analytics Case Study (Python)

## Overview
This project analyzes retail transaction data to identify opportunities to improve profit margins while maintaining revenue.

The analysis evaluates customer purchasing behavior, store performance, marketing campaign impact, and product strategy decisions to support data-driven business recommendations.

## Business Objective
Wayne Inc., a retail company with stores in New York and Los Angeles, wants to improve **profit margins without reducing revenue**.

The goal of this analysis is to answer four strategic business questions using transaction data.

## Business Questions
1. Identify the **Top 5 customers purchasing across multiple stores** for a targeted 10% discount campaign.
2. Evaluate the **impact of a TV marketing campaign** run from 1 Sep to 30 Sep 2012.
3. Identify a **store that could be closed with minimal financial impact**.
4. Evaluate the **impact of discontinuing Product C** assuming customers switch to Product A.

## Dataset
The dataset contains retail transaction records including:

- Customer_ID – Unique customer identifier  
- Transaction_date – Date of purchase  
- Order_ID – Unique order identifier  
- Revenue – Revenue generated from the order  
- Margin – Profit generated from the order  
- Product_ID – Product purchased  
- Units – Number of units purchased  
- Store_ID – Store location identifier  

## Project Structure

```
retail-sales-business-analysis
│
├── case-study
│   └── VOOT Business Analytics Case Study.pdf
│
├── data
│   └── Customer Analysis_Raw Data.csv
│
├── notebooks
│   └── retail_sales_analysis.ipynb
│
├── presentation
│   └── Retail-Sales-Business-Analysis.pptx
│
└── README.md
```
## Analysis Approach

The analysis was conducted using the following steps:

1. Data Cleaning
   - Converted date columns
   - Handled missing values
   - Verified dataset structure

2. Exploratory Data Analysis
   - Store performance analysis
   - Product revenue and margin analysis
   - Customer purchasing behavior

3. Business Analysis
   - Customer segmentation for marketing campaign
   - TV campaign revenue impact
   - Store closure impact assessment
   - Product substitution impact analysis

4. Visualization
   - Revenue by Store
   - Revenue by Product
   - Monthly Revenue Trend

## Sample Visualization

Revenue by Store

![Revenue by Store](images/store_revenue_chart.png)

## Key Insights

- **Top multi-store customers** were identified as ideal candidates for targeted discount campaigns.
- The **TV campaign increased revenue** during September 2012.
- **Store LA_333** is the weakest performing store and could be considered for closure with limited financial risk.
- **Product C should not be discontinued** as it contributes higher revenue and profit margin compared to Product A.

## Final Recommendations

**Customer Strategy**
Target high-value customers who purchase across multiple stores with personalized promotions.

**Marketing Strategy**
Continue TV marketing campaigns as they show measurable revenue impact.

**Store Strategy**
Consider closing LA_333 to reduce operational costs while maintaining most revenue through customer migration.

**Product Strategy**
Retain Product C as it contributes significantly to profitability.

## Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Author

Nikunj Agarwal  
