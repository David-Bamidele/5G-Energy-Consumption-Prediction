
# 5G Energy Consumption Prediction

This project focuses on predicting energy consumption in 5G networks using regression models. We implement five different regression algorithms to compare their performance in predicting energy usage based on given features such as network load, signal strength, user density, etc.

## Project Overview

The rapid expansion of 5G technology brings high bandwidth and low latency, but also higher energy demands. This project aims to predict energy consumption in 5G networks to enable network operators to optimize energy usage and manage resources efficiently. We utilized a dataset containing various metrics related to 5G network performance and applied the following regression techniques:

1. **Linear Regression**
2. **Ridge Regression**
3. **Support Vector Regression (SVR)**
4. **Gradient Boosting Regressor**

## Dataset

The dataset used for this project contains features such as:

- **Time**
- **Energy Cosumption**
- **Load**
- **ESMODE**
- **TXpower**
- **Time**

The target variable is **Energy Consumption (kWh)**.



## Models Used

1. **Linear Regression:**
   A basic regression model to establish a baseline.

2. **Ridge Regression:**
   A regularized version of linear regression that adds a penalty for large coefficients to reduce overfitting.

3. **Support Vector Regression (SVR):**
   SVR attempts to fit the best line within a margin that minimizes errors.

4. **Gradient Boosting Regressor:**
   A powerful ensemble method that builds models sequentially by combining weaker models to improve predictions.



 **Performance Evaluation:**

   The model performance is evaluated using metrics such as:

   - **Root Mean Squared Error (RMSE)**
   - **R² Score**


## Results

| Model                      | RMSE   | R²     |
|----------------------------|--------|--------|
| Linear Regression          | 4.1687 | 0.9084 |
| Ridge Regression           | 4.1687 | 0.9084 |
| Support Vector Regression  | 4.2167 | 0.9063 |
| Gradient Boosting Regressor| 3.5302 | 0.9343 |


From the above results, we can see that the **Gradient Boosting Regressor** performed best, with the lowest RMSE and highest R² score, indicating better predictive performance for energy consumption in 5G networks.

## Conclusion

This project demonstrates how different regression models can be applied to predict energy consumption in 5G networks. **Gradient Boosting Regressor** outperforms other models, suggesting that an ensemble approach is more effective for this type of problem.


## Requirements

- Python 3.8+
- scikit-learn
- numpy
- pandas
- matplotlib
- seaborn
- jupyter


## Author

- **David Bamidele** - Data Scientist

## License

This project is licensed under the MIT License - see the LICENSE file for details.
