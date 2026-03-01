# MSCS_634_Lab_4

This repository contains a Jupyter Notebook (`diabetes_regression_lab.ipynb`) exploring various regression techniques using the Diabetes dataset from `sklearn.datasets`.

## Purpose
The lab demonstrates simple linear regression, multiple regression, polynomial regression, and regularized models (Ridge and Lasso). It compares their performance using MAE, MSE, RMSE, and R², and visualizes predictions to understand model behavior.

## Key Insights
- Multiple regression outperforms simple linear regression using a single feature.
- Polynomial models can capture non-linear relationships, but higher degrees risk overfitting.
- Ridge and Lasso regularization reduce coefficient magnitude; Lasso can eliminate features.
- Regularization helps control overfitting by adjusting the alpha parameter.
- The Diabetes dataset exhibits moderate linear trends, and proper model choice improves predictive accuracy.

## Challenges
- Choosing the correct polynomial degree to balance bias and variance.
- Tuning alpha values for Ridge/Lasso to obtain meaningful improvements.

## Rubric Alignment
The notebook is structured to address each rubric category:
1. **Data Preparation:** dataset exploration, cleaning check, and explanation.
2. **Linear, Multiple, Polynomial Models:** implementations with metrics
   (MAE, MSE, RMSE, R²) and visualizations, along with interpretations.
3. **Ridge & Lasso:** alpha tuning, coefficient plots, and performance analysis.
4. **Model Comparison:** summarized table and discussions of overfitting.
5. **Documentation:** extensive comments and markdown ensure clarity and
   readability.

The notebook contains detailed code, outputs, and visualizations for each step.