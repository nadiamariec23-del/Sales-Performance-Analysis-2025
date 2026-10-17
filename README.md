
# Sales Performance Analysis | 2025

## Project Overview

This project analyzes a synthetic dataset containing 300 sales transactions from 2025 to evaluate revenue performance, identify sales trends, and uncover insights across product categories, geographical regions, and individual products.

Using Python, Pandas, and Matplotlib, I performed exploratory data analysis (EDA), calculated key performance indicators (KPIs), created visualizations, and developed business recommendations based on the findings.

The objective of this project is to demonstrate how raw transactional data can be transformed into meaningful insights that support data-driven business decisions.


## Key Project Results

This analysis examined 300 sales transactions from 2025 and identified the following key performance indicators (KPIs):

| Key Performance Indicator | Result |
|---|---|
| 💰 Total Sales Revenue | **$87,457** |
| 🛒 Total Transactions | **300** |
| 🏆 Highest Revenue Category | **Furniture — $51,250** |
| 📍 Highest Revenue Region | **North — $25,915** |
| 📅 Highest Revenue Month | **February — $11,460** |
| 📉 Lowest Revenue Month | **September — $4,112** |
| 🪑 Highest Revenue Product | **Desk — $28,210** |
| 📦 Most Units Sold | **Pens — 118 units** |

### Key Takeaway

Furniture accounted for approximately **58.6% of total revenue**, making it the strongest-performing product category.

February recorded the highest monthly revenue, while the North region generated the most revenue geographically.

The analysis also revealed that the product generating the highest revenue was not the product selling the most units, highlighting the importance of evaluating both revenue and sales volume.

## View the Full Analysis

[View Sales Performance Analysis 2025 in Google Colab](https://colab.research.google.com/drive/1zwEVkYKiMRkvwsL1u0WkSxvduYxl5qgP?usp=sharing)

The notebook includes Python code, data exploration, visualizations, business insights, and recommendations.

## Business Objectives

- Calculate overall sales revenue.
- Identify the highest revenue-generating product categories.
- Analyze monthly revenue trends and fluctuations.
- Compare sales performance across geographical regions.
- Identify top-performing products based on revenue and quantity sold.
- Develop business recommendations based on the findings.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and calculations |
| Pandas | Data manipulation, exploration, and aggregation |
| Matplotlib | Data visualization |
| Google Colab | Development environment |
| GitHub | Project documentation and code sharing |

## Dataset Description

The dataset contains 300 fictional sales transactions recorded throughout 2025.

### Dataset Columns

| Column | Description |
|---|---|
| order_id | Unique identifier for each transaction |
| order_date | Date of purchase |
| region | Geographic region where the sale occurred |
| category | Product category |
| product | Individual product purchased |
| quantity | Number of units sold |
| unit_price | Selling price per unit |

An additional `revenue` column was calculated using:

```python
df["revenue"] = df["quantity"] * df["unit_price"]
```

**Note:** This dataset is synthetic and was created for educational and portfolio purposes. It does not represent actual company sales.

## Data Analysis Methodology

### 1. Data Exploration and Quality Checks

- Imported the dataset using Pandas.
- Examined the dataset structure and column names.
- Reviewed sample transactions.
- Checked for missing values across all columns.
- Converted order dates into a format suitable for time-based analysis.

### 2. Revenue Calculation

Calculated revenue for each transaction using:

`Revenue = Quantity × Unit Price`

Aggregated individual transactions to determine total sales revenue.

### 3. Revenue by Product Category

Grouped sales transactions by product category to identify the categories generating the highest revenue.

### 4. Monthly Revenue Analysis

Aggregated revenue by month to identify fluctuations, peak-performing periods, and sales trends throughout 2025.

### 5. Regional Sales Analysis

Compared revenue generated across the North, South, East, and West regions to identify differences in sales performance.

### 6. Product Performance Analysis

Evaluated individual products based on:

- Total revenue generated
- Total quantity sold

This comparison helped identify differences between high-revenue and high-volume products.

## Key Findings & Business Insights

### 1. Overall Sales Performance

**Total Sales Revenue: $87,457**

The dataset generated $87,457 in total sales revenue across 300 transactions.

### 2. Revenue by Product Category

| Product Category | Total Revenue | Revenue Share |
|---|---:|---:|
| Furniture | $51,250 | 58.6% |
| Electronics | $30,573 | 35.0% |
| Office Supplies | $5,634 | 6.4% |
| **Total** | **$87,457** | **100%** |

**Business Insight:**

Furniture was the largest revenue-generating category, accounting for approximately 58.6% of total revenue.

Electronics contributed 35.0%, while Office Supplies represented 6.4%.

These findings indicate that furniture products are major revenue drivers within the dataset.

### 3. Monthly Sales Trends

- **Highest Revenue Month:** February — $11,460
- **Lowest Revenue Month:** September — $4,112
- Monthly revenue fluctuated throughout 2025.
- Revenue increased consistently from October through December.

**Business Insight:**

February generated the highest monthly revenue, while September recorded the lowest.

These fluctuations highlight opportunities to investigate potential seasonal patterns, promotional activity, and changes in customer demand.

Additional information would be necessary to determine the specific causes of these changes.

### 4. Regional Sales Performance

| Region | Total Revenue | Revenue Share |
|---|---:|---:|
| North | $25,915 | 29.6% |
| West | $23,618 | 27.0% |
| South | $21,775 | 24.9% |
| East | $16,149 | 18.5% |

**Business Insight:**

The North region generated the highest revenue, contributing approximately 29.6% of total sales.

The East region generated the lowest revenue, accounting for approximately 18.5%.

Further analysis of order volume, average order value, and customer demand could help explain these regional differences.

### 5. Product Performance

| Performance Metric | Product | Result |
|---|---|---|
| Highest Revenue | Desk | $28,210 |
| Highest Sales Volume | Pens | 118 units |

Desks and office chairs generated a combined $47,110 in sales revenue.

**Business Insight:**

Desks generated the highest revenue, while pens recorded the highest number of units sold.

This demonstrates that products with the highest sales volume do not necessarily generate the greatest revenue.

Product pricing plays an important role in overall revenue performance.

## Business Recommendations

### 1. Strengthen High-Revenue Product Categories

Investigate opportunities to sustain strong furniture sales and assess whether additional marketing or inventory investment could support future growth.

### 2. Investigate Monthly Revenue Fluctuations

Analyze factors that may have contributed to February's revenue peak and September's decline, including seasonal demand, promotions, and purchasing patterns.

### 3. Evaluate Regional Sales Opportunities

Examine regional order volumes, average order values, and customer demand to better understand performance differences and identify potential growth opportunities.

### 4. Balance Revenue and Sales Volume

Evaluate both revenue and quantity sold when making product, inventory, and marketing decisions.

High-volume products may contribute differently to overall business performance than higher-priced products.

## Project Limitations

- The dataset is synthetic and does not reflect actual business performance.
- Product costs and profit margins are unavailable, preventing profitability analysis.
- Customer-level information is unavailable, limiting customer behavior analysis.
- The dataset does not establish the causes of monthly or regional revenue fluctuations.
- Findings are descriptive and should not be interpreted as causal relationships.

## How to Run the Project

1. Open the Google Colab notebook using the link provided near the beginning of this README.
2. Download the `sales.csv` file from this GitHub repository.
3. Upload the CSV file into the Google Colab working directory.
4. Select **Runtime → Run all** to execute the Python code.
5. Review the resulting calculations, visualizations, and business insights.

### Required Python Libraries

- Pandas
- Matplotlib

## Skills Demonstrated

- Python programming
- Exploratory Data Analysis (EDA)
- Data quality checks
- Data manipulation using Pandas
- Revenue and KPI calculations
- Data aggregation and grouping
- Time-series analysis
- Data visualization with Matplotlib
- Business performance evaluation
- Analytical reporting
- Data-driven business recommendations

## Conclusion

This project demonstrates my foundational skills in Python-based data analysis, data visualization, and business intelligence.

Through the analysis of 300 synthetic sales transactions, I transformed raw transactional data into structured insights highlighting revenue trends, product performance, and regional differences.

The project strengthened my ability to use analytical tools, interpret business metrics, communicate findings, and develop recommendations that support informed business decision-making.
