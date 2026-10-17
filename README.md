
# Sales Performance Analysis | 2025

## Project Overview

This project analyzes a synthetic sales dataset containing 300 transactions from 2025 to identify revenue trends, product performance, and regional sales patterns.

Using Python, Pandas, and Matplotlib, I explored the dataset, calculated key performance indicators (KPIs), created visualizations, and developed business recommendations based on the findings.

The goal of this project is to demonstrate my ability to transform raw data into meaningful business insights.

## Business Objectives

- Analyze overall sales revenue.
- Identify the highest revenue-generating product categories.
- Examine monthly sales trends and fluctuations.
- Compare revenue performance across geographical regions.
- Identify top-performing products by revenue and units sold.
- Develop actionable business recommendations.

## Tools & Technologies

- **Python:** Data analysis and calculations
- **Pandas:** Data cleaning, manipulation, and aggregation
- **Matplotlib:** Data visualization
- **Google Colab:** Development environment
- **GitHub:** Project documentation and version control

## Dataset

The dataset contains 300 fictional sales transactions from 2025.

The original dataset includes the following columns:

| Column | Description |
|---|---|
| order_id | Unique identifier for each transaction |
| order_date | Date of purchase |
| region | Geographic sales region |
| category | Product category |
| product | Product purchased |
| quantity | Number of units purchased |
| unit_price | Selling price per unit |

An additional revenue column was calculated using:

```python
df["revenue"] = df["quantity"] * df["unit_price"]
```

**Note:** This is a synthetic dataset created for educational and portfolio purposes. It does not represent actual company sales.

## Data Analysis Process

1. Imported the CSV dataset using Pandas.
2. Explored the dataset and checked for missing values.
3. Calculated total revenue.
4. Analyzed revenue by product category.
5. Examined monthly revenue trends.
6. Compared regional sales performance.
7. Evaluated individual products by revenue and quantity sold.
8. Created visualizations and documented business insights.

## Key Findings

### 1. Overall Sales Performance

**Total Revenue: $87,457**

### 2. Revenue by Product Category

| Category | Revenue |
|---|---:|
| Furniture | $51,250 |
| Electronics | $30,573 |
| Office Supplies | $5,634 |

Furniture contributed approximately 58.6% of total revenue, making it the largest revenue-generating category.

### 3. Monthly Sales Trends

- **Highest Revenue Month:** February — $11,460
- **Lowest Revenue Month:** September — $4,112
- Revenue fluctuated throughout the year.
- Revenue increased consistently between October and December.

### 4. Regional Sales Performance

| Region | Revenue |
|---|---:|
| North | $25,915 |
| West | $23,618 |
| South | $21,775 |
| East | $16,149 |

The North region generated the highest revenue, accounting for approximately 29.6% of total sales.

### 5. Product Performance

- **Highest Revenue Product:** Desk — $28,210
- **Highest Sales Volume Product:** Pens — 118 units
- Desks and office chairs generated a combined $47,110 in revenue.

The analysis demonstrates that selling more units does not necessarily mean generating more revenue.

## Business Recommendations

1. **Furniture Performance:** Investigate opportunities to maintain and strengthen revenue from furniture products.
2. **Monthly Sales Trends:** Examine potential reasons for February's revenue peak and September's decline.
3. **Regional Performance:** Analyze order volume and average order value to better understand differences across regions.
4. **Product Strategy:** Evaluate revenue and units sold together when making product and inventory decisions.

## Project Limitations

- The dataset is synthetic and does not represent real company performance.
- Profit margins and product costs are unavailable, so profitability cannot be evaluated.
- The dataset does not provide sufficient information to determine the causes of revenue fluctuations.
- Findings are descriptive and should not be interpreted as causal relationships.

## How to Run the Project

1. Download the `Sales_Performance_Analysis_2025.ipynb` and `sales.csv` files.
2. Open the notebook in [Google Colab](https://colab.research.google.com/).
3. Upload `sales.csv` to the Colab working directory.
4. Run the notebook cells in order to reproduce the analysis and visualizations.

The notebook uses these Python libraries:

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## Conclusion

This project demonstrates my foundational skills in Python programming, data exploration, data manipulation, data visualization, and business analysis.

Through this analysis, I practiced turning transactional sales data into clear visualizations and data-driven recommendations that can support business decision-making.
  
