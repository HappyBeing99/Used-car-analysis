# Used-car-analysis – Exploratory Data Analysis Project

📌 Objective - 
This project performs a complete exploratory data analysis on a real-world used car listings dataset.
The goal is to understand pricing drivers, market patterns, vehicle conditions, and geographic differences in car sales.

1. Data Ingestion & Quality Profiling

Loaded dataset into Pandas, Inspected datatypes, null percentages, duplicate rows, Identified structural data issues (VIN values inside state column), Validated ranges (year, odometer, condition, price), Fixed corrupted rows and applied targeted imputations

2. Data Cleaning

Trimmed whitespace, normalized text columns, Imputed missing categorical values (mode or "unknown"), Imputed numeric values with medians, Removed corrupted state values, Removed VIN-invalid rows, Converted saledate to datetime, Created car_age feature

3. Exploratory Data Analysis

Correlation heatmap of numerical features, Average price by year, Price vs odometer scatterplot, State-wise inventory distribution, Condition-based segment analysis, Boxplot of price by color (before & after outlier removal)

4. Insights

Newer and better-condition cars sell significantly higher, Odometer (mileage) has a strong negative impact on price, Some states consistently list higher-priced cars, Most cars fall into mid-to-high condition ranges, Outliers heavily skew color-based price distributions, Certain makes offer better “value-for-money” at high condition levels

💡 Tools & Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
