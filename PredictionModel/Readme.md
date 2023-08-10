# Sales Forecasting Model using Linear Regression

This repository contains a Python script that demonstrates a sales forecasting model using linear regression. The model is implemented to predict future sales based on historical data, providing insights for business planning and decision-making.

## Prerequisites

- `numpy` library: Install it using `pip install numpy`
- `pandas` library: Install it using `pip install pandas`
- `matplotlib` library: Install it using `pip install matplotlib`
- `scikit-learn` library: Install it using `pip install scikit-learn`
## Model Implementation

The sales forecasting model is implemented in the `Sales_forecasting.ipynb` script. The key steps of the implementation include:

1. Loading and Preprocessing Data:
   - Load the prepared sales dataset using `pandas`.
   - Preprocess and engineer features such as time-based variables, promotions, and holidays.

2. Linear Regression Model:
   - Implement a linear regression model using the `LinearRegression` class from `scikit-learn`.
   - Define input features (independent variables) and the target variable (sales).

3. Training and Testing:
   - Split the dataset into training and testing sets.
   - Train the linear regression model using the training data.

4. Prediction and Visualization:
   - Use the trained model to predict future sales on the test data.
   - Visualize the predicted sales against the actual sales using `matplotlib`.
