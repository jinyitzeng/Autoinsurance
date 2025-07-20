## Project Overview
This project predicts auto insurance claim amounts using machine learning models.
A zero-inflated dataset was filtered to focus on positive claims, and models were trained to predict claim expenses.

## Goals
Predict non-zero insurance claim amounts

Compare regression models for performance

Identify key predictors influencing claim costs

## Tools Used
R (tidymodels, glmnet, randomForest)

Quarto

ggplot2

## Key Files
insurance_claims_modeling.qmd – Main analysis code

final_report.pdf – Modeling summary and results

## Modeling Summary
Applied regularised regression (Lasso), K-Nearest Neighbors (KNN), and Random Forest models

Target variable was log-transformed to improve prediction

Models evaluated using 10-fold cross-validation and RMSE

Best performance achieved using regularised regression
