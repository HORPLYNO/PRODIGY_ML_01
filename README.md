# PRODIGY_ML_01
This repository contains a **Linear Regression model** that predicts house prices based on the square footage, number of bedrooms, and bathrooms.

## 📌 Task
The goal is to **predict house prices** using the following features:
- Square footage of the house
- Number of bedrooms
- Number of bathrooms
## Data Preparation

Read the dataset using Pandas.

Checked for missing values and duplicate rows.

Verified data types

Created a new dataset using only relevant features.

##  Exploratory Data Analysis (EDA)

Generated descriptive statistics to understand data distribution.

Plotted scatter plots between sqft_living and price to visualize the relationship.

Used box plots to detect outliers in sqft_living, bedrooms, and bathrooms.

Calculated Pearson correlation coefficients to analyze relationships between features.

Created a heatmap to visualize feature correlations.

##  Model Training

Split the dataset into training and testing sets using Scikit-learn.

Implemented a Linear Regression model to predict house prices.

Extracted model coefficients to interpret feature importance.

##  Model Evaluation

Used R-squared score to measure model accuracy.

Calculated Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

Compared predicted values with actual values using visual plots.

## 📝 Additional Information
- The model performance suggests that **R-squared = 0.5148**, meaning the model explains about **51% of the variance** in house prices.
- 
