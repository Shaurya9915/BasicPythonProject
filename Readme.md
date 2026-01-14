Customer Data Analysis
This project explores customer behavior using a dataset of 1,362 entries with features like age, income, spending score, membership years, purchase frequency, and last purchase amount. The goal is to uncover insights that can guide business strategy, especially around customer retention and revenue growth.

Dataset Overview
Rows: 1,362

Columns: 7

Fields include:

Number – unique customer ID

Age – customer age

Income – annual income

Spending_Score – spending behavior metric

Membership_Years – years of membership

Purchase_Frequency – average purchase frequency

Last_Purchase_Amount – amount spent in last purchase

Data Cleaning
Removed duplicate entries using df.drop_duplicates(inplace=True)

Verified no missing values across all columns (df.info() shows 0 nulls)

Key Metrics & Insights
Revenue concentration – A small number of customers contribute a large share of revenue.

Repeat customers matter – Higher purchase frequency is linked to higher average revenue.

Retention focus – Longer membership years correlate with stronger spending, so retention strategies are critical.

Analysis Performed
Correlation checks between income, spending score, and purchase frequency

Top customers identified by last purchase amount and spending score

Age group analysis to compare average spending across demographics

Customer segmentation potential based on frequency and membership years

Tech Stack
Python: Pandas, Matplotlib

Jupyter Notebook for interactive analysis
