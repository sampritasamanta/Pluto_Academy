# Project 02 – House Prices Sale Price Prediction

## Overview

This project was completed as part of the Pluto Academy AI & ML Internship Program.

The objective is to build regression models to predict house sale prices using the House Prices – Advanced Regression Techniques dataset from Kaggle.

## Dataset

The dataset contains information about residential properties in Ames, Iowa.

- Training samples: 1,460
- Features: 80
- Target variable: `SalePrice`

## Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Missing-value handling
4. Categorical feature encoding
5. Feature and target separation
6. Train-test split
7. Model training
8. Model evaluation and comparison
9. Best model analysis using residuals
10. Final conclusion

## Models Used

Three regression models were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Best Model

Gradient Boosting achieved the best performance among the three evaluated models based on the comparison results.

A residual plot was used to analyze the prediction errors of the selected model.

## Files

- `House_Prices_Regression.ipynb` – Complete Google Colab notebook containing preprocessing, feature engineering, model training, evaluation, comparison, visualization, and conclusion.

## Source

House Prices – Advanced Regression Techniques, Kaggle.
