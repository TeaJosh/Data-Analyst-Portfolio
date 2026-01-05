# Car Sales Analysis

**Description:** This project explores automotive sales data to uncover market trends and customer purchasing behaviors. Analyzing 23,906 transactions across 7 regions and multiple dealerships, the project identifies key factors influencing vehicle pricing, understands demographic purchasing patterns, reveals seasonal sales trends, and evaluates dealer performance. Statistical testing through correlation analysis, chi-square tests, and t-tests validates findings and supports business recommendations.

**Tools:** RStudio and R Markdown.

**Skills:** Data importing, data cleaning, feature engineering (temporal decomposition, ratio calculations), descriptive statistics, correlation and hypothesis testing, data aggregation and manipulation, time series analysis, customer segmentation, data visualization, business reporting.

**Outputs:**

    Analysis notebook in .ipynb format containing project details, exploratory analysis, statistical tests, visualizations, and conclusions.

## Datasets

    car_sales.csv - automotive sales transactions
        Fields: 16 (expanded to 21 with feature engineering)
        Rows: 23,906
        Regions: 7 (Austin, Pasco, Scottsdale, Aurora, Greenville, Janesville, Middletown)
        Date Range: January 2022 - December 2023

Key Variables:
- Customer demographics: gender, annual income ($13,500 - $4,700,000+)
- Vehicle specs: manufacturer, model, body style, transmission, color, price ($3,750 - $85,000)
- Dealer information: name, region
- Engineered features: month, year, quarter, day of week, price-to-income ratio, income segments

## Acknowledgements

Dataset sourced from Kaggle for educational and analytical purposes.
