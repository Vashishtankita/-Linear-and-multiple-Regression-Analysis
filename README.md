# Demand Prediction using Linear Regression

This project demonstrates a simple linear regression model to predict demand based on stock levels.

## Dataset
- **demand_stock.data.csv**: Contains information on stock levels and demand.

## Project Workflow
1. Load the dataset and explore it for missing values and data types.
2. Select **Stock** as the feature and **Demand** as the target variable.
3. Train a Linear Regression model on the data.
4. Evaluate the model using Mean Squared Error (MSE) and R² Score.
5. Visualize the predictions and residuals.

## Results
Linear regression-
- **Mean Squared Error**: 0.8887235474970236
- **R² Score**: 0.6702928653566578

Multiple regression-
- **Mean Squared Error**: 0.4522479816837192
- **R² Score**: 0.9751106638519218
  

## Insights
- Positive relationship between **Stock** and **Demand**.
- A potential negative relationship between **Price** and **Demand** (if included).
