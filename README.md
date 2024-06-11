# Sales-Analysis-and-Statistical-Testing-for-Revenue-Growth

Overview
This project analyzes sales growth trends in California by comparing total sales between 2017 and 2018. Using a comprehensive dataset from a company's sales across 49 states between 2015 and 2018, the study aims to identify significant changes in sales and specific product categories contributing to these trends through various statistical tests.

Dataset
Source: Superstore Sales Dataset (available on Kaggle)
Features: Order Date, Sales, Category, State, Postal Code
Installation
To run the notebook, ensure you have the following dependencies installed: pandas, numpy, seaborn, matplotlib, scipy.

Usage
Clone the repository from GitHub.
Navigate to the project directory.
Open the Jupyter Notebook and run the cells to perform the analysis.

Methods
Data Preparation
Standardize Columns: Convert all column names to lowercase.
Clean Data: Remove duplicates, standardize string values, convert dates, fill missing postal codes, ensure numeric sales data.

Analysis
Filter Data: Focus on California, split data into 2017 and 2018.
EDA: Perform exploratory data analysis using histograms, box plots, and point plots.
Statistical Tests:
Shapiro-Wilk Test for normality.
Bootstrap Confidence Intervals.
Mann-Whitney U Test for sales comparison.
Kruskal-Wallis Test for product categories.

Results
Normality Test: High skewness and kurtosis for both years.
Confidence Intervals: Overlapping intervals suggest no significant difference.
Mann-Whitney U Test: No significant difference in overall sales.
Kruskal-Wallis Test: Significant difference in furniture sales (p = 0.026).

Conclusion
There is no significant increase in overall sales from 2017 to 2018, but there is a significant decrease in furniture sales in 2018. Further research is needed to understand the factors influencing these trends.
