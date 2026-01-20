# WEEK 2 

# Sales Data Analysis Dashboard

# 📌 Project Description-

This project analyzes a real-world sales dataset to extract actionable business insights using Python-based data analysis and visualization techniques. The dashboard highlights sales trends over time, best-selling product categories, regional performance, and customer purchasing behavior.
The entire analysis is implemented in a Jupyter Notebook using Pandas, Matplotlib, and Seaborn.

# 🛠 Tech Stack -

Language: Python
Libraries: Pandas, Matplotlib, Seaborn
Environment: Jupyter Notebook

# 📂 Dataset Details-

Source: CSV file (sales_data_sample.csv)
Records: 2823 rows
Features: 25 columns including:
ORDERNUMBER,	QUANTITYORDERED,	PRICEEACH,	ORDERLINENUMBER,	SALES,	ORDERDATE,	
STATUS,	QTR_ID,	MONTH_ID,	YEAR_ID,	...	ADDRESSLINE1,	ADDRESSLINE2,	CITY,	STATE,	POSTALCODE,	COUNTRY	TERRITORY,	CONTACTLASTNAME,	CONTACTFIRSTNAME,	DEALSIZ


# 🔧 Data Preprocessing-

The following data cleaning and feature engineering steps were performed:
Converted column names to lowercase and removed whitespace
Removed missing values in critical columns (sales, orderdate)
Converted orderdate to datetime format
Extracted:
 month from order date
 year from order date

# 📊 Visualizations & Analysis-

1️⃣ Monthly Sales Trend
    Line plot showing monthly sales trends
    Comparison across years (2003–2005)
    Identifies seasonal peaks and sales growth patterns

2️⃣ Top-Selling Product Categories
    Bar chart of total sales by productline
    Identifies Classic Cars and Vintage Cars as top contributors

3️⃣ Top 10 Countries by Sales
    Horizontal bar chart of sales by country
    Reveals USA as the highest revenue-generating market

4️⃣ Customer Deal Size Distribution
    Count plot of dealsize (Small, Medium, Large)
    Shows majority of orders fall under Medium deals

5️⃣ Year-wise Total Sales
    Bar chart comparing total sales across years
    Indicates 2004 as the highest performing year

6️⃣ Revenue Contribution by Deal Size
    Pie chart representing sales share by deal size
    Medium deals contribute the largest revenue portion

7️⃣ Sales Heatmap (Month vs Year)
    Heatmap showing sales intensity by month and year
    Highlights strong sales periods visually

# 📁 Project Structure-

Sales-Data-Analysis-Dashboard/
│
├── sales_data_sample.csv
├── Sales_Data_Analysis.ipynb
└── README.md

# ▶️ How to Run the Project-

1.Clone or download the repository
2.Install required libraries:
  pip install pandas matplotlib seaborn
3.Open Sales_Data_Analysis.ipynb in Jupyter Notebook
4.Run cells sequentially to reproduce the analysis and visualizations

# 📈 Key Insights-

1. Sales peak consistently in later months of the year
2. Classic Cars dominate product sales
3. USA leads significantly in total revenue
4. Medium deal sizes generate maximum revenue
5. Year 2004 recorded the highest overall sales

# ✅ Conclusion-

This project demonstrates effective use of data cleaning, aggregation, and visualization to analyze sales performance. The insights obtained can support business decision-making, market strategy, and sales optimization.
