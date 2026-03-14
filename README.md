# Amazon Product Analytics Dashboard

Interactive **Power BI dashboard and Python-based exploratory data analysis (EDA)** of Amazon product data to understand category performance, customer ratings, and discount patterns.

---

## Project Overview

This project analyzes Amazon product data to explore how different product categories perform, how discounts vary across categories, and whether discounts influence customer ratings.

The workflow includes **data cleaning, exploratory data analysis using Python, and interactive dashboard development using Power BI**.

---

## What I Did

- Cleaned and preprocessed Amazon product data (ratings, discounts, and pricing fields)
- Performed exploratory data analysis using Python
- Analyzed the relationship between **discount percentage and product ratings**
- Built an interactive **Power BI dashboard** with KPI metrics and category comparisons
- Extracted business insights from rating and discount patterns

---

## Dashboard Metrics

- **Total Products:** 1351  
- **Total Reviews:** 27M  
- **Average Rating:** 4.10  
- **Average Discount:** 47.69%  
- **Average Price:** 3.13K  

---

## Visual Analysis

The dashboard includes the following visualizations:

- Product distribution across categories
- Average rating comparison by category
- Average discount comparison by category
- Scatter plot showing the relationship between **discount percentage and ratings**
- Table of **top reviewed products**

---

## Key Insight

Higher discounts **do not significantly increase product ratings**.

Most products maintain ratings between **4.0 – 4.5 stars**, suggesting that **product quality and customer experience influence ratings more than pricing strategies**.

---

## Business Insights

**Discounts ≠ Higher Ratings**  
Discounting may increase purchase probability but does not significantly improve perceived product quality.

**Stable Rating Distribution**  
Most categories cluster between **4.0–4.5 stars**, indicating relatively consistent product satisfaction.

**Category Prioritization**  
Categories such as **Electronics, Computers, and Home** contain the highest number of products and provide opportunities for targeted optimization strategies.

**Review-Driven Trust**  
Products with high review counts build stronger customer trust and should be highlighted in recommendation systems or marketing strategies.

---

## Tools Used

- Python
- Pandas
- Power BI
- Data Cleaning
- Data Visualization
- Business Intelligence

---

## Repository Structure

-amazon-product-analysis
-│
-├── dashboard
-│ └── amazon_product_analytics_dashboard.pbix
-│
-├── data
-│ └── amazon_cleaned_data.csv
-│
-├── images
-│ └── dashboard screenshots
-│
-├── notebook
-│ └── amazon_analysis.ipynb
-│
-└── README.md



## Project Files

- `data/amazon_cleaned_data.csv` — cleaned dataset  
- `notebook/amazon_analysis.ipynb` — exploratory analysis  
- `dashboard/amazon_product_analytics_dashboard.pbix` — Power BI dashboard  
- `images/` — dashboard screenshots
