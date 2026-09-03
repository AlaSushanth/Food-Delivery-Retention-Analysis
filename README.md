# Food Delivery Retention & Growth Analysis

![Power BI Dashboard](Food_Delivery_Retention_Growth_Dashboard.png.png)

Food delivery customer retention analysis using Python, Power BI, and customer segmentation.

Food delivery customer retention and growth analysis using Python, customer segmentation, and Power BI.

## Project Overview

This project analyzes food delivery order history to understand customer retention, repeat-order behaviour, and the factors that influence customers to order again.

The analysis focuses on identifying high-value customers, understanding customer churn risk, discovering reorder patterns, and estimating the potential business impact of improving repeat-order rates.

## Business Objectives

- Measure customer retention and repeat-order behaviour.
- Understand how quickly customers place their next order.
- Identify factors associated with repeat purchases.
- Compare customer behaviour across different segments.
- Identify customers who may be at risk of becoming inactive.
- Evaluate a simulated retention experiment.
- Estimate the potential revenue and contribution from improving retention.
- Present the findings through an interactive Power BI dashboard.

## Dataset

The project uses food delivery order history data from Kaggle.

The dataset contains customer-level order information used to analyse:

- Customer order frequency
- Order dates and reorder intervals
- Order value and revenue contribution
- Discount usage
- Customer complaints
- First-order status
- Restaurant-level retention
- Customer recency and risk segments

## Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Customer-level feature engineering
5. Retention and reorder analysis
6. Customer segmentation
7. Retention-driver analysis
8. Simulated A/B test analysis
9. Business-impact estimation
10. Power BI dashboard development

## Key Analysis Performed

### 1. Customer Retention Analysis

Customers were classified based on their ordering behaviour to understand the proportion of one-time and repeat customers.

The analysis also examined revenue contribution across customer lifecycle segments.

### 2. Reorder Behaviour

The project analysed:

- Time taken to place the next order
- Reorder windows
- Consecutive reorder intervals
- Customer ordering frequency

This helps identify the period when retention campaigns may be most effective.

### 3. Retention Drivers

The following factors were compared with repeat-order behaviour:

- Discount usage on the first order
- Complaints during the first order
- First-order status
- Restaurant-level retention

These comparisons help identify possible areas for improving customer experience and retention.

### 4. Customer Risk Segmentation

Customers were segmented using recency, frequency, and spending behaviour.

The segmentation helps identify:

- High-value customers
- Active customers
- Customers showing signs of inactivity
- Customers who may require re-engagement campaigns

### 5. Simulated A/B Test

A simulated A/B test was used to compare repeat-order rates between a control group and a treatment group.

The analysis includes:

- Control and treatment repeat rates
- Difference in repeat rates
- Statistical significance
- Confidence interval
- Group sizes

The experiment is simulated for analytical practice and should not be interpreted as a real-world causal experiment.

### 6. Business Impact Estimation

The project estimates the potential impact of improving customer repeat-order rates.

The estimation includes:

- Potential incremental revenue
- Estimated incremental contribution
- Assumed contribution margin

These figures are illustrative estimates based on the analysis assumptions.

## Key Findings

- The dataset contains **21,321 orders** from **11,607 customers**.
- The overall repeat-customer rate is approximately **33.55%**.
- One-time customers account for approximately **66.45%** of customers.
- Repeat customers contribute a significant share of total revenue.
- Approximately **66.56%** of eventual repeat customers reorder within 30 days.
- Approximately **85.39%** of eventual repeat customers reorder within 60 days.
- Customers who used a discount on their first order showed a slightly higher repeat rate.
- Customers who raised a complaint during their first order showed a substantially lower repeat rate.
- The simulated treatment group showed a higher repeat rate than the control group, but the result was not statistically significant.
- Improving retention may create additional revenue by increasing the number of repeat orders.

## Power BI Dashboard

The Power BI dashboard contains five pages.

### 1. Executive Overview

Provides a high-level summary of:

- Total customers
- Total revenue
- Customer lifecycle distribution
- Revenue contribution by segment
- Reorder timing
- Discount usage and repeat rate

### 2. Retention & Reorder Behaviour

Shows:

- Reorder timing distribution
- Consecutive reorder intervals
- Complaint status versus repeat behaviour
- First-order status versus repeat behaviour

### 3. Retention Drivers

Examines the relationship between repeat orders and:

- Discount usage
- Customer complaints
- First-order status
- Restaurant retention

### 4. Customer Risk Segmentation

Displays:

- Customer count by risk segment
- Revenue contribution by risk segment
- Average recency
- Average customer spending

### 5. Experiment & Business Impact

Includes:

- Simulated A/B test repeat rates
- Control and treatment group sizes
- Estimated incremental revenue
- Estimated incremental contribution

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Microsoft Excel

## Repository Contents

- `Food_Delivery_Retention_Product_Analytics.ipynb` — Complete Python analysis notebook
- `Food_Delivery_Retention_Growth_Analysis.pbix` — Power BI dashboard file
- `Food_Delivery_Retention_Growth_Dashboard.pdf` — Exported dashboard
- `Food_Delivery_PowerBI_Summary_Tables.xlsx` — Summary tables used in Power BI
- `dashboard.png` — Dashboard preview image

## Important Note

The A/B test and business-impact calculations are simulated and illustrative. They are intended to demonstrate analytical and business decision-making skills and are not based on a live experiment or production intervention.

## Author

Sushanth Kumar Reddy
