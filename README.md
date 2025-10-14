# Data Analytics Project: Discount Strategy Analysis

## Project Overview
This project analyzes three key datasets — `orders.csv`, `products.csv`, and `orderlines.csv` — to determine whether implementing aggressive discount strategies would positively impact overall revenue.

## Objective
The primary goal is to evaluate if offering higher discounts can drive increased revenue, or if such strategies may lead to diminished returns due to reduced profit margins.

## Data Sources
- **orders.csv**: Contains order-level information such as order date, customer, and total value.
- **products.csv**: Includes product details such as product name, category, and base price.
- **orderlines.csv**: Provides line-item details for each order, linking products with orders and discounts applied.

## Key Analysis Areas
- Correlation between discount rates and revenue
- Impact of discounts on revenue and sales
- Discount rates of products generating highest & lowest revenue
- Product-specific analysis: Product with highest revenue and product with highest sales

## Findings Summary
While discount is beneficial for the company, going aggessive does not guarantee an increase in the revenue. 
- Many examples indicate that the sales/revenue do not always increase when high discounts are offered
- Taking seasonality (such as Summer break & Christmas seasons) into consideration when discounting products is beneficial

## Visual Insights
The project includes following visual figures that support the findings:

### Share of Discounted Products in the Revenue
![pie_chart](/images/discount_revenue.png)

### Discount Vs (Revenue & Sales) 
![sales_revenue_vs_discount](/images/sales_revenue_vs_discount.png)

### Average Discount of Highest and Lowest Revenue Generating Products 
![top_bottom_5_products_revenue](/images/top_bottom_5_products_revenue.png)

### Discount Vs Revenue for the Highest Revenue Generating Product
![top_revenue_product](/images/top_revenue_product.png)

### Discount Vs Revenue for the Most Sold Product
![top_sales_product](/images/top_sales_product.png)

## How to Reproduce
1. Clone the repository
2. Create the environment using the `environment.yml` file
3. Run the `data_analysis.ipynb` file on your IDE 

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook / Data Analysis Platform
