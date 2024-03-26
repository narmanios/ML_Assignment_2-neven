# Assignment 2: Regularization Parameter Analysis

## Overview
In this assignment, we explore the effects of varying the regularization parameter on different performance measures and implemented in `my_measures.py`. The focus is on the `alpha` parameter of the `RidgeClassifier()` class.

## Objectives
- Understand the impact of regularization on model performance.
- Experiment with different values of the `alpha` parameter and observe their effects on performance measures.

## Model
The model used in this analysis is the `RidgeClassifier` from `sklearn.linear_model`. The regularization parameter `alpha` is varied to observe its effect on the model's performance.

## Experiments
The following `alpha` values were tested: 0.0000001, 10, 100, 1000, 10000, 100000. Performance measures such as accuracy, precision, and recall were calculated for both training and test sets.

## Usage
To replicate the experiments, run the provided Jupyter notebook. Ensure that you have all the required packages installed and that your dataset is properly formatted.

## Dependencies
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib (for plotting)

## Author
Neven Armanios
