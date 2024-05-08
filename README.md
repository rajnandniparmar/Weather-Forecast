# Weather Forecast

This project aims to forecast `BASEL_temp_mean` using time series analysis and machine learning techniques.

## Problem Statement

The goal is to predict `BASEL_temp_mean` accurately, considering its temporal dependencies and potential seasonality.

## Data

The dataset (`data11.xlsx`) contains historical temperature data (`BASEL_temp_mean`) with dates as the index.

## Approach

- **Initial Attempts:**
  - Experimented with Autoregressive (AR), Moving Average (MA), ARIMA, and Seasonal ARIMA (SARIMA) models.
  - These models failed to capture the data dynamics effectively, resulting in significant Root Mean Squared Error (RMSE) values.

- **Linear Regression:**
  - Applied Linear Regression to explore simple modeling approaches.
  - However, the linear regression model exhibited signs of overfitting and was not suitable for this dataset.

- **Current Focus:**
  - Recognizing the limitations of linear models, the project is now focusing on non-linear machine learning models.
  - Exploring advanced techniques such as tree-based models (e.g., Random Forest, Gradient Boosting) and neural networks to capture complex patterns in the data.

## Next Steps

- Implement and evaluate non-linear models to improve forecast accuracy.
- Conduct feature engineering to extract relevant information from the dataset.
- Optimize model hyperparameters and assess performance using appropriate evaluation metrics.



