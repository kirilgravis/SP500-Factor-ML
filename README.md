# SP500-Factor-ML

## Project Overview

**SP500-Factor-ML** is a project aimed at forecasting the S&P 500 index using machine learning techniques and fundamental factors. The project leverages key financial indicators such as inflation rates, bond yields, price-earnings (P/E) ratios, and market liquidity to predict future market trends.

## Objectives

- To analyze and forecast the S&P 500 index using a combination of fundamental factors and machine learning models.
- To evaluate the effectiveness of different models including Linear Regression, Random Forest, and XGBoost.
- To visualize the results and provide insights into feature importance.

## Data Sources

This project uses a combination of publicly available financial data, including:

- **Liquidity data:** Key liquidity metrics for market movement analysis.
- **Main financial data:** Historical prices, inflation rates, bond yields, and P/E ratios.
- **Technical indicators:** RSI (Relative Strength Index), moving averages, and percentage changes.

## Project Workflow

1. **Data Collection & Preparation**
   - Load and clean liquidity data and main financial data.
   - Join datasets and align time series.

2. **Feature Engineering**
   - Calculate technical indicators such as RSI, percentage change, and moving averages.
   - Add relevant macroeconomic indicators as features.

3. **Model Training**
   - Split the data into training and test sets.
   - Implement machine learning models:
     - **Linear Regression**
     - **RandomForestClassifier**
     - **XGBoost**

4. **Hyperparameter Tuning**
   - Perform grid search for the best parameters for decision trees and XGBoost.

5. **Model Evaluation**
   - Evaluate models using appropriate metrics (e.g., R-squared for regression, accuracy for classification).
   - Extract feature importance from the models.

6. **Visualization & Interpretation**
   - Visualize model predictions and important features.
   - Provide insights into the main factors driving the forecasts.

## Key Features

- **Feature Engineering:** Custom technical indicators (RSI, moving averages) and macroeconomic variables.
- **Machine Learning Models:** Linear regression, Random Forest, XGBoost with grid search for hyperparameter tuning.
- **Feature Importance:** Analyze which factors contribute most to the model’s predictions.
- **Visualization:** Graphical representations of results and decision tree visualizations.

## Contact

For any inquiries, feel free to reach out via email or through GitHub.

