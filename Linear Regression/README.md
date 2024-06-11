# Linear Regression

## Overview
This project showcases an advanced application of linear regression techniques using the Boston house prices dataset from Scikit Learn. By leveraging both foundational and innovative regression methods, this project successfully predicts housing prices with precision, demonstrating a mastery of applied machine learning.

## Dataset
The dataset used is the renowned Boston house prices dataset, consisting of 506 instances with 13 attributes each and one target value. Key attributes include:
- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centres
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in $1000’s

## Features
1. **Comprehensive Data Analysis**:
   - Conducted an in-depth exploration of the dataset utilizing Scikit Learn and Numpy, uncovering significant patterns and insights.

2. **Advanced Linear Regression Modeling**:
   - Developed a robust linear regression model to accurately estimate house prices.
   - Utilized k-fold cross-validation to ensure the model's reliability and stability, achieving high performance on both training and test datasets using solely Numpy.

3. **Optimized Ridge Regression**:
   - Implemented an optimized ridge regression model, meticulously selecting the best λ through k-fold cross-validation, resulting in superior predictive accuracy.

4. **Enhanced Feature Engineering**:
   - Applied a polynomial transformation of degree 2 to the dataset features, significantly improving the model's predictive power.

5. **Gradient Descent Implementation**:
   - Demonstrated proficiency in optimization techniques by executing a multivariate linear regression using the Gradient Descent method.

6. **Implementation of Regularization Techniques**:
   - Expertly implemented Lasso and Elastic Net regression models, fine-tuning them to balance model complexity and performance.

7. **Strategic Model Selection**:
   - Conducted a rigorous evaluation of various models, selecting the most effective one for future housing price predictions based on performance metrics and model parameters.

## Instructions for Running the Project
1. Ensure all required libraries are installed (`numpy`, `scikit-learn`, etc.).
2. Execute the provided scripts sequentially to replicate the project's results:
   - Data exploration and linear regression model
   - Ridge regression with cross-validation
   - Polynomial feature transformation and regression
   - Gradient descent optimization
   - Lasso and Elastic Net implementations
3. Detailed instructions and explanations are available in the accompanying project report.