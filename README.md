# Data_Analysis_Satscores

# SAT Score Analysis Across U.S. States

This project analyzes SAT score data from various U.S. states to explore how educational and socioeconomic variables relate to student performance. The analysis combines descriptive statistics, data visualization, and linear regression modeling.

The analysis includes:
**Data Import & Cleaning**: Reading `.sav` file, handling missing values, creating categorical variables.
**Descriptive Statistics**: Summary statistics, histograms, skewness, kurtosis, and coefficient of variation.
**Bivariate Analysis**: Spearman correlation between SAT scores and variables like cost, salary, percent participation, etc.
**Visualization**: Histograms, bar plots, heatmaps, and diagnostic plots for regression models.
**Regression Modeling**: Building and evaluating linear models to explain or predict SAT Total score using predictors like COST and PERCENT.
**Model Assumption Checks**: Linearity, homoscedasticity (Levene's test), normality of residuals (Shapiro-Wilk test), and influential points.

Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scipy)
- Data file format: `.sav` (SPSS)
- 
# Notes

- The dataset includes variables such as `COST`, `RATIO`, `SALARY`, `PERCENT`, `VERBAL`, `MATH`, and `TOTAL`.
- Linear models were compared and validated through both statistical tests and graphical diagnostics.
- A logarithmic transformation was applied to improve model linearity.

# Disclaimer # 
I can't upload the dataset because i don't have the permission to do it. The repo contains ONLY the code I made.
