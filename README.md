# SC5002 Lab Assignment 1

This repository contains the Jupyter notebook for SC5002 Lab Assignment 1 completed by Sun Haosheng.

## Overview
This assignment focuses on applying a low-code machine learning workflow using the California Housing dataset. The notebook demonstrates several key steps commonly used in practical ML tasks, including:

- loading and sampling the dataset,
- preparing feature and target variables,
- standardizing inputs for modeling,
- training and comparing regression models,
- evaluating performance using cross-validation,
- visualizing model comparison results.

## Repository Contents
- `SC5002LabAssignmnet1_SunHaosheng.ipynb` — the main notebook with the assignment implementation
- `README.md` — project overview and documentation

## Dataset Used
The notebook uses the California Housing dataset from scikit-learn:

- `fetch_california_housing(as_frame=True)`
- The dataset contains housing-related features such as median income, house age, room counts, population, latitude, and longitude.
- The target variable is `MedHouseVal` (median house value).

## Machine Learning Workflow
The notebook includes:

1. Data loading and dataset sampling
2. Feature-target splitting
3. Standard scaling of numerical features
4. Train/test split for evaluation
5. Linear Regression model training
6. Ridge Regression with multiple alpha values
7. 5-fold cross-validation using R² score
8. Performance comparison chart

## Model Comparison
The assignment compares:

- Linear Regression
- Ridge Regression with alpha values of 0.1, 10.0, and 1000.0

The results are evaluated using the mean 5-fold cross-validation R² score.

## Key Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Project Purpose
This repository serves as a record of the machine learning lab assignment and can be used as a reference for:

- exploring real-world tabular datasets,
- evaluating baseline and regularized models,
- interpreting model performance using cross-validation,
- presenting results through visualization.

## Author
Sun Haosheng

## Repository
https://github.com/Haosheng333/SC5002LabAssignmnet1_SunHaosheng
