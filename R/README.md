# Car Sales Analysis

**Description:** This comprehensive exploratory analysis examines automotive sales data to uncover critical market trends, customer purchasing behaviors, and dealer performance metrics. Using RStudio for statistical analysis and visualization, the project analyzes 23,906 transactions across 7 regions and multiple dealers to identify key factors influencing vehicle pricing, understand demographic purchasing patterns, reveal seasonal sales trends, and evaluate regional performance disparities. Statistical testing through correlation analysis, chi-square tests of independence, and independent samples t-tests validates key findings and supports data-driven business recommendations.

**Tools:** RStudio (tidyverse, janitor, lubridate, ggplot2)

**Key Analyses:**
- Exploratory data analysis with descriptive statistics
- Feature engineering (temporal decomposition, ratio calculations)
- Correlation analysis (income vs. price relationship)
- Hypothesis testing (chi-square tests for gender-preference associations, t-tests for transmission pricing)
- Time series analysis (monthly sales trends and growth patterns)
- Customer segmentation (income-based quartiles, demographic profiling)
- Dealer performance benchmarking
- Regional sales performance comparison
- Data visualization (histograms, scatter plots, boxplots, bar charts)

**Skills Demonstrated:** Data importing and cleaning, feature engineering, exploratory statistics, correlation and regression analysis, categorical hypothesis testing, parametric hypothesis testing, data aggregation and grouping, time series decomposition, customer segmentation, multivariate visualization, business intelligence reporting.

**Outputs:**
- Analysis notebook in `.ipynb` format containing:
  - Phase 1: Data exploration, unique entity verification, and quality validation
  - Phase 2: Feature engineering and temporal decomposition
  - Phase 3: Multi-dimensional statistical analysis and visualizations
  - Phase 4: Comprehensive conclusions and business implications

**Key Findings:**
- Price range: $3,750 to $85,000 (mean ≈ $27,800)
- Gender significantly influences body style and price range preferences (p < 0.05)
- Automatic transmissions command significantly higher prices than manual transmissions (p < 0.05)
- Weak positive correlation between customer income and purchase price (r ≈ 0.1-0.3)
- Distinct seasonal patterns in monthly sales volume
- High-income customers (top 25%) contribute disproportionately to total revenue
- Significant regional performance disparities among dealerships

## Dataset

**File:** `car_sales.csv`

**Size:** 23,906 transactions across 7 regions (Austin, Pasco, Scottsdale, Aurora, Greenville, Janesville, Middletown)

**Time Period:** January 2022 - December 2023 (24 months)

**Fields:** 16 raw fields, expanded to 21 with feature engineering

**Key Variables:**

*Customer Demographics:*
- Gender (Male, Female)
- Annual Income ($13,500 - $4,700,000+)

*Vehicle Specifications:*
- Company (manufacturer)
- Model
- Body Style (sedan, SUV, truck, coupe, hatchback, wagon, etc.)
- Transmission (Automatic, Manual)
- Color
- Price ($3,750 - $85,000)

*Dealer Information:*
- Dealer Name
- Dealer Region

*Temporal:*
- Transaction Date (aggregated by month, quarter, day of week)

*Engineered Features:*
- Month, Year, Quarter, Day of Week
- Price-to-Income Ratio
- Income Segments (Low, Middle, High Income based on quartiles)

## Acknowledgements

Dataset sourced from Kaggle for educational and analytical purposes.
