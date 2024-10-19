# Multiple Linear Regression for Demand Prediction

## Overview

This project implements a **multiple linear regression model** to predict demand based on various supply-related factors. It demonstrates the end-to-end process of preparing data, building, and evaluating a linear regression model using Python.

## Dataset
- **Dataset Name:** demand_supply.data.csv  
- **Description:** The dataset contains information on different features that influence demand. The objective is to predict demand based on these factors.
- **Missing Values:** Checked and handled in the notebook.

## Libraries Used
- `pandas`: Data manipulation and analysis
- `numpy`: Numerical computations
- `matplotlib` & `seaborn`: Data visualization
- `scikit-learn`: Model building and evaluation

## Project Workflow

1. **Data Loading:**  
   The dataset is loaded using `pandas` and inspected for missing values and basic statistics.

2. **Exploratory Data Analysis (EDA):**  
   Visualizations are used to explore the relationships between features and the target variable (demand).

3. **Data Preprocessing:**  
   - Missing values are checked and handled.
   - Features are defined by dropping the `Demand` column.
   - The target variable is the `Demand`.

4. **Model Development:**  
   - The dataset is split into training (80%) and testing (20%) sets.
   - A multiple linear regression model is trained using the **LinearRegression** class from `scikit-learn`.

5. **Model Evaluation:**  
   - Performance metrics such as **Mean Squared Error (MSE)** and **R² Score** are calculated to assess the model’s effectiveness.
