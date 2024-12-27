# Heart Failure Prediction

This project focuses on predicting heart failure using a comprehensive dataset of patient information. The analysis is performed using SAS (Statistical Analysis System) to preprocess, explore, and model the data for accurate predictions.

## Project Overview

The Heart Failure Prediction project aims to develop a predictive model for identifying patients at risk of heart disease. The analysis includes data preprocessing, exploratory data analysis, and logistic regression modeling.


## Methodology

The project follows these main steps:

1. **Data Import and Preprocessing**: The dataset is imported using the INFILE method in SAS. Variables are encoded and labeled appropriately.

2. **Exploratory Data Analysis**: Various statistical and visual analyses are performed, including:
   - Histograms
   - Scatter plots
   - Correlation matrices
   - Box plots

3. **Logistic Regression Modeling**: A full logistic regression model is initially built, followed by iterative refinement to address outliers and influential points.

4. **Model Selection**: Backward selection method is employed to identify the most significant predictors.

5. **Model Validation**: The dataset is split into training (75%) and testing (25%) sets to validate the model's performance.

6. **Predictions**: The final model is used to make predictions on new data points.
