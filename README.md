# E-Commerce Sales Data Analysis and Reporting System
## Overview

This project implements a complete ETL pipeline and analytics solution for an e-commerce company. It loads sales data from multiple CSV files, cleans and validates the data, performs customer segmentation using RFM analysis, projects customer lifetime value (CLV), analyzes retention cohorts, and generates a professional LaTeX report with 10 actionable business insights.

---

## Key Features

- Modular ETL pipeline with data validation and cleaning
- RFM customer segmentation and behavioural archetypes
- Projected CLV with zero-order customers included
- Cohort retention analysis over 24 months
- 10 actionable business insights with recommendations
- Professional LaTeX report with visualizations
- All outputs exported as CSV files

---

## Key Results

| Metric | Value |
|--------|-------|
| Total Revenue | $254,065,824 |
| Total Orders | 925 |
| Unique Customers (with orders) | 199 |
| Total Customers (including zero-order) | 200 |
| Average Order Value (AOV) | $274,665.76 |
| Repeat Customer Rate | 94.0% |
| Top Category (Revenue) | Electronics – $74,613,394 |
| Top Region (Revenue) | West – $56,618,498 |
| Champions + Loyal Revenue Contribution | 39.6% |
| Projected CLV – High-Value Regulars | $2,425,420 |

---

## Technologies

- Python 3.8+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scipy
- LaTeX (Overleaf compatible)

---

## Data Sources

- `customers.csv` – Customer details
- `products.csv` – Product catalogue
- `orders.csv` – Order headers
- `order_items.csv` – Order line items

---

## Insights Summary

The analysis produced 10 key business insights, including:

1. West region has the highest AOV despite similar order counts to other regions.
2. 94.0% repeat buyers but 39.5% hibernating customers – a large reactivation opportunity.
3. Correlation between tenure and revenue is nearly zero (0.031) – tenure is a poor predictor of value.
4. Champions and Loyal customers (27% of base) contribute 39.6% of revenue.
5. Sports category is 78% below Electronics – a strategic decision point.
6. Weekday AOV differences are not statistically significant (p=0.192).

All insights are detailed in the report with supporting data and actionable recommendations.

---

## Statistical Validations

- Correlation (tenure vs revenue): 0.031
- t-test (Thursday vs Wednesday AOV): p = 0.192
- Revenue contribution (Champions + Loyal): 39.6%

---

## License

MIT License

---

## Acknowledgements

- Mr. Prateek Khandelwal – for providing the problem statement, guidance and mentorship
- Systango – for providing the opportunity

---

## Contact

- Shravan Jaiswal
- https://in.linkedin.com/in/shravan-jaiswal-6542061b0
