# Online Food Delivery Customer Analysis

## Project Overview

This project analyses customer behaviour in an online food delivery dataset using Python, SQL and statistical analysis.

The objective is to identify customer characteristics associated with online food ordering and translate the findings into practical business recommendations.

## Business Questions

* What percentage of customers order food online?
* Which age groups have the highest ordering rates?
* Which occupations have the highest ordering rates?
* Is gender associated with online ordering?
* Is marital status associated with online ordering?
* Is customer feedback associated with online ordering?
* Does income differ between customers who order online and those who do not?
* Which customer characteristics are useful for customer segmentation?

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* DuckDB
* SQL
* Jupyter Notebook

## Analysis Process

1. Data loading
2. Data inspection
3. Data cleaning
4. Exploratory data analysis
5. Data visualization
6. Statistical testing
7. SQL analysis
8. Business recommendations

## Key Findings

Approximately 76% of customers in the dataset reported ordering food online.

Age group, occupation, marital status and customer feedback showed statistically significant associations with online food ordering.

Customer feedback produced the strongest chi-square result among the categorical variables tested.

Gender, educational qualifications, customer type and family size did not show statistically significant associations with online food ordering at the 5% significance level.

Younger customers and students showed higher ordering rates in the descriptive analysis.

## Statistical Analysis

Chi-square tests were used to examine associations between categorical customer characteristics and online food ordering.

Mann-Whitney U tests were used to compare numerical variables between customers who ordered online and those who did not.

A significance level of 0.05 was used.

## Business Recommendations

The findings suggest that food delivery businesses should:

* Focus digital marketing on younger customers
* Develop targeted student promotions
* Monitor customer feedback closely
* Investigate negative feedback
* Segment campaigns by occupation
* Examine differences across marital-status groups
* Avoid relying heavily on gender for customer targeting

## Project Structure

```text
online-food-delivery-analysis/
│
├── README.md
├── online_food_delivery_analysis.ipynb
│
├── data/
│   └── online_food_delivery_cleaned.csv
│
└── sql/
    └── business_analysis.sql
```

## Conclusion

The analysis demonstrates how Python, SQL, visualization and statistical testing can be combined to transform customer data into actionable business insights.

The findings describe associations within the dataset and should not be interpreted as evidence of causal relationships.
