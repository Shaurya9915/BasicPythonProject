# BasicPythonProject
Retail Sales Analysis – Amazon.csv
This project analyzes transactional retail data from Amazon.csv using Python and Jupyter Notebook. It demonstrates data cleaning, business metric computation, category analysis, time-based trends, and visualization — ideal for portfolio showcasing and business insight generation.

**Dataset Overview**
Rows: 1,000

Columns: 17

**Fields include:**  
Invoice ID, Branch, City, Customer type, Gender, Product line, Unit price, Quantity, Tax 5%, Total, Date, Time, Payment, cogs, gross margin percentage, gross income, Rating

Data Cleaning
Removed duplicates: df.drop_duplicates(inplace=True)

Checked for nulls: All columns have 0 missing values

Core Business Metrics
Metric	Value
Total Revenue	₹322,966.75
Average Order Value (AOV)	₹322.97
Order Count	1,000 unique invoices

Category/Product Line Analysis
Product Line	Revenue (₹)
Health and beauty	49,199.73
Home and lifestyle	53,801.91
Fashion accessories	54,306.60
Electronic accessories	54,337.85
Sports and travel	55,132.53
Food and beverages	56,144.84

Food and beverages is the top-performing category; Health and beauty is the lowest.

Monthly Sales Trend
Grouped by month using df["Date"].dt.month

Visualized with a line chart titled "Monthly Sales Trend"

Observation:

Month 1: High sales

Month 2: Dip

Month 3: Recovery
→ Indicates possible seasonality

Visualization
Bar chart: Category wise Revenue

Created using df.groupby("Product line")["Total"].sum().plot(kind="bar")

Highlights revenue distribution across categories

Export
Category revenue exported to CSV using:

python
df.groupby("Product line")["Total"].sum().to_csv("sales.ipynb")
Tech Stack
Python: Pandas, Matplotlib

Jupyter Notebook

Dataset: Amazon.csv  (1000 rows × 17 columns)

Key Insights
Top category (Food and beverages) contributes ~17% of total revenue

Sales dip in month 2, suggesting seasonal variation

AOV of ₹322.97 implies a mid-range pricing strategy


Open Retail_Analysis.ipynb in Jupyter Notebook

Run all cells to reproduce analysis and visualizations
