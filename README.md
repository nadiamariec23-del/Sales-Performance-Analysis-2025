
# Sales Performance Analysis | 2025

## Project Overview

This project analyzes a synthetic sales dataset containing 300 transactions from 2025 to identify revenue trends, product performance, and regional sales patterns.

Using Python, Pandas, and Matplotlib, I explored the dataset, calculated key performance indicators (KPIs), created data visualizations, and developed business recommendations based on the findings.

The goal of this project is to demonstrate my ability to transform raw sales data into meaningful business insights that support data-driven decision-making.

## View the Full Analysis

**[Open My Sales Performance Analysis Notebook in Google Colab](https://colab.research.google.com/drive/1zwEVkYKiMRkvwsL1u0WkSxvduYxl5qgP?usp=sharing)**

The Google Colab notebook includes Python code, data exploration, revenue calculations, visualizations, business insights, and recommendations.

## Business Objectives

- Calculate overall sales revenue.
- Identify the highest revenue-generating product categories.
- Analyze monthly sales trends and fluctuations.
- Compare revenue performance across geographical regions.
- Identify top-performing products by revenue and units sold.
- Develop business recommendations based on the results.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and calculations |
| Pandas | Data manipulation, aggregation, and exploration |
| Matplotlib | Creating data visualizations |
| Google Colab | Writing and executing Python code |
| GitHub | Project documentation and code sharing |

## Dataset

The dataset contains 300 fictional sales transactions from 2025 and was created for educational and portfolio purposes.

### Dataset Columns

| Column | Description |
|---|---|
| order_id | Unique identifier for each sales transaction |
| order_date | Date the order was placed |
| region | Geographic region where the sale occurred |
| category | Product category |
| product | Product purchased |
| quantity | Number of units sold |
| unit_price | Selling price per unit |

An additional `revenue` column was calculated using:

```python
df["revenue"] = df["quantity"] * df["unit_price"]
```

**Note:** This is synthetic data and does not represent actual company sales.

## Data Analysis Process

### 1. Data Import and Exploration

- Imported the CSV dataset using Pandas.
- Reviewed the first rows of the dataset.
- Examined its structure and columns.
- Checked for missing values.

### 2. Revenue Calculation

Calculated sales revenue for each transaction by multiplying quantity by unit price, then summed the results to determine total revenue.

### 3. Product Category Analysis

Grouped transactions by category to determine which product categories contributed the most revenue.

### 4. Monthly Revenue Analysis

Converted order dates into datetime format and grouped transactions by month to identify revenue trends throughout 2025.

### 5. Regional Sales Analysis

Compared total revenue across the North, South, East, and West regions.

### 6. Product Performance Analysis

Compared individual products using two metrics:

- Total revenue generated.
- Total number of units sold.

### 7. Data Visualization

Created bar charts and a line chart using Matplotlib to communicate the findings.

## Key Findings

### Overall Sales Performance

**Total Revenue: $87,457**

### Revenue by Product Category

| Product Category | Revenue | Share of Revenue |
|---|---:|---:|
| Furniture | $51,250 | 58.6% |
| Electronics | $30,573 | 35.0% |
| Office Supplies | $5,634 | 6.4% |
| **Total** | **$87,457** | **100%** |

**Insight:** Furniture generated the largest share of revenue, accounting for approximately 58.6% of total sales.

### Monthly Sales Trends

- **Highest Revenue Month:** February — $11,460.
- **Lowest Revenue Month:** September — $4,112.
- Monthly revenue fluctuated throughout 2025.
- Revenue increased consistently from October through December.

**Insight:** The differences in monthly performance suggest opportunities to investigate seasonality, purchasing patterns, and possible promotional effects.

### Regional Sales Performance

| Region | Revenue | Share of Revenue |
|---|---:|---:|
| North | $25,915 | 29.6% |
| West | $23,618 | 27.0% |
| South | $21,775 | 24.9% |
| East | $16,149 | 18.5% |

**Insight:** The North region generated the highest revenue, while the East region generated the lowest. Additional analysis would be necessary to understand the reasons for these differences.

### Product Performance

| Metric | Leading Product | Result |
|---|---|---|
| Highest Revenue | Desk | $28,210 |
| Highest Sales Volume | Pens | 118 units |

Desks and office chairs generated a combined $47,110 in revenue.

**Insight:** Products with the highest sales volume do not necessarily generate the most revenue. Higher-priced products may produce significantly more revenue despite selling fewer units.

## Business Recommendations

### 1. Strengthen High-Revenue Categories

Investigate opportunities to maintain strong furniture sales and assess whether additional marketing or inventory investment could support growth.

### 2. Investigate Monthly Sales Fluctuations

Explore potential factors behind February's revenue peak and September's decline, including promotions, demand changes, and seasonal patterns.

### 3. Evaluate Regional Performance

Analyze order volume, average order value, and customer demand across regions to identify opportunities for improvement.

### 4. Compare Revenue and Sales Volume

Evaluate both total revenue and quantity sold when making inventory, marketing, and product strategy decisions.

## Project Limitations

- The dataset is synthetic and does not represent actual company performance.
- Product costs and profit margins are unavailable, so profitability cannot be determined.
- Customer-level information is unavailable, limiting customer behavior analysis.
- The dataset does not establish the causes of monthly or regional performance differences.

## How to Run the Project

1. Open the [Sales Performance Analysis notebook in Google Colab](https://colab.research.google.com/drive/1zwEVkYKiMRkvwsL1u0WkSxvduYxl5qgP?usp=sharing).
2. Download the `sales.csv` dataset from this GitHub repository.
3. Upload `sales.csv` into the Google Colab working directory.
4. Select **Runtime → Run all** to execute the analysis.
5. Review the generated tables, visualizations, and business insights.

### Required Python Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## Skills Demonstrated

- Python programming
- Data exploration
- Data quality checks
- Data manipulation with Pandas
- Revenue and KPI calculations
- Grouping and aggregating data
- Time-series analysis
- Data visualization with Matplotlib
- Business insight development
- Data-driven recommendations

## Conclusion

This project demonstrates my foundational skills in Python-based data analysis and business intelligence.

By analyzing 300 synthetic sales transactions, I practiced transforming raw transactional data into meaningful insights through calculations, visualizations, and business recommendations.

The project strengthened my ability to evaluate sales performance, identify trends, and communicate analytical findings in a clear and structured manner.

---

**[View the Complete Analysis in Google Colab](https://colab.research.google.com/drive/1zwEVkYKiMRkvwsL1u0WkSxvduYxl5qgP?usp=sharing)**
  
