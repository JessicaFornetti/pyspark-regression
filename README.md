# pyspark-regression

This project uses PySpark on the Databricks platform to predict Paris real estate prices on the [Paris Housing Price Prediction](https://www.kaggle.com/datasets/mssmartypants/paris-housing-price-prediction) Kaggle dataset.

The main steps are outlined below:

- **Part 1 : Problem Definition, Kaggle Competition selected and why**
- **Part 2 : Data Exploration, Feature Engineering and Data Preparation** - Data exploration is carried out using SQL querries and their associated graphs
- **Part 3:  Model creation** - Linear Regression, Decision Tree Regressor, Random Forest Regressor and Gradient Boosted Tree Regressor models were built using 5 fold cross validation and a grid search to find the best hyperparameters for each model
- **Part 4: Model Evaluation and Explanations of Decision** - The models are compared and evaluated on the following metrics : R squared, Root Mean Squared Error, Mean Squared Error, Mean Absolute Error and Explained Varriance. The predictions of each model are inspected and a comparaison between the predictions and the real labels is plotted, as well as the residuals plot and the distribution of the residuals.
- **Part 5: Discussion of work completed, competition outcomes, and highlighting features of Spark used**

# Project Overview
This repository contains 2 notebooks, a [Jupyter Notebook](Big%20Data%20Assignment.ipynb) and a [Databricks Notebook](Big%20Data%20Assignment%20-%20Databricks%20notebook.html).
