# 🏋️‍♂️ Gym Member Fitness Data Preparation & Exploration

This Jupyter Notebook contains comprehensive data cleaning and exploratory analysis performed on a gym member dataset. The dataset includes over 4,000 samples of member exercise sessions, physical attributes, and performance metrics.

## 📌 Project Context

A gym operator is seeking to analyze the relationship between demographic, physiological, and behavioral factors and the number of **calories burned** during workout sessions. The analysis supports downstream predictive modeling (done in **SAS Viya**) to identify key contributors to calorie expenditure and athlete progression across experience levels.

## 🧹 What's in the Notebook

✔️ Data loading and inspection  
✔️ Handling missing values and duplicates  
✔️ BMI consistency check and recalculation  
✔️ Outlier detection and removal    
✔️ Visual analyses such as correlation matrix and scatterplots

The dataset is prepared in a way that allows it to be directly exported and used for model training in SAS Viya without additional transformation.

## 📌 Notes

- No feature scaling/normalization was applied to preserve interpretability for linear regression modeling.
- Experience level is treated as an **ordered categorical variable** to support ordinal relationships in modeling.
