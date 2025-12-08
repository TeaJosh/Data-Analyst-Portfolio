# Car Sales Analysis

**Description:** This project analyzes car sales data to uncover trends in customer preferences, pricing dynamics, and sales patterns. The analysis examines 23,906 transactions across 7 regions to identify key factors influencing car pricing and sales, understand customer demographics and purchasing behavior, analyze temporal trends, and evaluate dealer performance. Statistical testing includes correlation analysis, chi-square tests, and t-tests to validate findings and provide actionable business recommendations.

**Tools:** RStudio (tidyverse, janitor, lubridate, ggplot2).

**Skills:** Data importing and cleaning, feature engineering (date manipulation, ratio calculations), descriptive statistics, correlation analysis, hypothesis testing (chi-square, t-tests), data aggregation and grouping, time series analysis, customer segmentation, data visualization, business reporting.

**Outputs:**
- Analysis notebook in `.ipynb` format containing data preparation, exploratory analysis, statistical tests, visualizations, and business insights.

## Dataset

- `car_sales.csv` - car sales transactions
  - Fields: 16 (expanded to 21 with feature engineering)
  - Rows: 23,906
  - Date Range: January 2022 - December 2023
  - Key Variables: customer demographics (gender, income), vehicle specs (company, model, body style, transmission, color, price), dealer info (name, region), transaction date

## Key Findings

- Gender significantly influences body style and price range preferences (p < 0.05)
- Automatic transmissions command higher average prices than manual transmissions
- Weak positive correlation between customer income and vehicle price (r = 0.012)
- Austin region leads in total revenue, followed by Janesville and Scottsdale
- SUVs and automatic transmissions dominate market preferences
- Strong seasonal patterns identified in sales volume and pricing

## Acknowledgements

Dataset sourced from Kaggle for educational and analytical purposes.
