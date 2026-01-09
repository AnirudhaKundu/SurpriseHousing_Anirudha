# Surprise Housing – House Price Prediction using Regularised Regression

## Table of Contents
- General Information
- Business Objective
- Dataset Information
- Approach
- Conclusions
- Technologies Used
- Acknowledgements
- Contact

## General Information
Surprise Housing is a US-based housing company planning to enter the Australian real estate market. The company follows a data-driven strategy to purchase properties below their actual value and resell them at a higher price.

This project focuses on building a regression model with regularisation techniques to predict house prices based on available property features. The model helps identify the key variables influencing house prices and supports strategic investment decisions in a new market.

## Business Objective
- Identify variables that significantly influence house prices  
- Understand how these variables impact pricing  
- Build a robust and generalisable predictive model  
- Determine optimal regularisation parameters for Ridge and Lasso regression  

## Dataset Information
- Housing sales dataset containing numerical and categorical features  
- Features include property size, quality, condition, location, and amenities  
- Target variable: SalePrice  
- Dataset requires missing value treatment, categorical encoding, and feature scaling  

## Approach
1. Data cleaning and preprocessing  
2. Feature engineering and encoding  
3. Train-test split to avoid data leakage  
4. Ridge and Lasso regression with cross-validation  
5. Model interpretation and robustness checks  

## Conclusions
- Property quality, living area, floor space, garage capacity, and premium neighbourhoods are key price drivers  
- Lasso regression is preferred for interpretability and feature selection  
- Regularisation improves model generalisability  
- The model remains robust even after removing top predictors  

## Technologies Used
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

## Acknowledgements
- Academic assignment on regression and regularisation  
- Dataset from urgrad AI ML course

## Contact
Created by [@AnirudhaKundu] — feel free to contact me for collaboration or questions!
