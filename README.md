# Data Cleaning and Exploratory Data Analysis Report

This report outlines the comprehensive data cleaning and exploratory data analysis (EDA) performed on the Titanic dataset using Python. Initially, the dataset was loaded using Seaborn, and its structure was inspected through a display of the first few rows, detailed info, and summary statistics. Missing values were identified, with the numerical column `age` imputed with its median and the categorical column `embarked` filled using its mode. The `deck` column, being categorical, was updated by adding a new category `"Unknown"` before filling its missing values to avoid errors.

Duplicate records were then removed to maintain data integrity. Outlier detection was implemented on the `age` and `fare` columns using the Interquartile Range (IQR) method, and extreme values were eliminated accordingly. Additionally, categorical variables such as `sex` and `embarked` were standardized to ensure consistency across the dataset.

For EDA, univariate analysis was conducted using histograms, box plots, and frequency distributions. Bivariate relationships were explored through correlation matrices, scatter plots, and bar plots, while multivariate analysis was performed using pair plots and heatmaps. Finally, the cleaned and enhanced dataset was saved as a CSV file, preparing it for further predictive modeling and in-depth analysis.
