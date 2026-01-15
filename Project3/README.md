Tools & Technologies Used

Python

Pandas – data cleaning & transformation

NumPy – numerical operations

Matplotlib / Seaborn – data visualization

Jupyter Notebook

Dataset Information

Source: Kaggle – Brazilian E-Commerce Public Dataset by Olist

Orders: ~100,000

Time Period: 2016–2018

Key Tables Used:

Orders

Customers

Payments

Deliveries

Key Analysis Performed
1️ Data Cleaning

Converted timestamp columns to datetime

Handled missing delivery dates

Removed invalid or incomplete orders

2️ Feature Engineering

Created new business-relevant metrics:

actual_delivery_days

estimated_delivery_days

delivery_delay_days

Delivery status:

Early

On-time

Delayed

3️ KPI Analysis

Average delivery delay

% of delayed deliveries

Distribution of delivery time

Early vs late delivery trends

4 Business Insights

Identified logistics bottlenecks

Compared estimated vs actual delivery performance

Highlighted customer impact due to delays

Sample Metrics

Average delivery delay (days)

Percentage of delayed orders

Difference between promised vs actual delivery

Delivery reliability indicators

Key Business Insights

A significant portion of orders are delivered later than estimated

Delivery delays directly impact customer satisfaction

Certain delivery windows show higher risk of delay

Estimation logic can be improved for better reliability
