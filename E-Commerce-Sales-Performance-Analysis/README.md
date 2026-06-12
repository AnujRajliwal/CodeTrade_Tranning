# E-Commerce Sales Performance Analysis

## Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on the Brazilian E-Commerce Public Dataset by Olist.

The goal is to analyze sales performance, customer behavior, product trends, seller performance, payment preferences, and geographic patterns to generate actionable business insights.

---

## Business Objective

The objective of this project is to identify patterns and trends in e-commerce sales data and provide recommendations that can improve business performance and support data-driven decision-making.

---

## Dataset

Source:
Brazilian E-Commerce Public Dataset by Olist

Files Used:

- olist_customers_dataset.csv
- olist_orders_dataset.csv
- olist_order_items_dataset.csv
- olist_products_dataset.csv
- olist_order_payments_dataset.csv
- olist_order_reviews_dataset.csv
- olist_sellers_dataset.csv
- product_category_name_translation.csv

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Imported all datasets
- Explored structure and dimensions
- Reviewed data types

### 2. Data Cleaning

- Missing value analysis
- Duplicate record checks
- Datetime conversion
- Data quality validation

### 3. Exploratory Data Analysis

The following business questions were analyzed:

1. Highest Revenue Product Categories
2. Sales Performance by Region
3. Customer Segmentation Analysis
4. Customer Purchasing Behavior
5. Top Products by Sales and Revenue
6. Payment Method Analysis
7. Seller Performance Analysis
8. Review Score Analysis
9. Sales Trends Over Time
10. Repeat Customer Analysis
11. Data Quality Assessment
12. Merge Reliability Validation

---

## Key Insights

- A small number of product categories generate the majority of revenue.
- Revenue is concentrated in a limited number of states.
- VIP customers contribute significantly more revenue than regular customers.
- Most customers are one-time buyers.
- Credit cards dominate transaction volume and revenue.
- Top sellers contribute a large portion of marketplace revenue.
- Customer review scores are generally positive.
- Seasonal sales trends are visible across different time periods.

---

## Visualizations

The project includes:

- Bar Charts
- Line Charts
- Histograms
- Box Plots
- Review Analysis Charts
- Revenue Analysis Charts
- Customer Behavior Visualizations

---

## Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── notebook/
│   └── EDA_Project.ipynb
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── products.csv
│   ├── payments.csv
│   ├── reviews.csv
│   └── sellers.csv
│
├── outputs/
│   ├── top_category_revenue.csv
│   ├── state_revenue_summary.csv
│   ├── customer_segment_analysis.csv
│   ├── payment_method_analysis.csv
│   ├── seller_revenue_analysis.csv
│   └── merge_integrity_report.csv
│
├── README.md
└── report.pdf
```

---

## Business Recommendations

- Increase marketing investment in top-performing product categories.
- Strengthen retention strategies for high-value customers.
- Expand operations in high-performing regions.
- Improve customer retention through loyalty programs.
- Support top-performing sellers with growth initiatives.
- Monitor low-rated categories to improve customer satisfaction.

---

## Author

Anuj Rajliwal

Aspiring Data Analyst | Python | SQL | Pandas | Data Visualization
