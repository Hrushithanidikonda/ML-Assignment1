# ML-Assignment1
# Wine Quality Prediction using Random Forests

This project uses the **Wine Quality dataset** and a **Random Forest Classifier** to predict the quality of red wine based on physicochemical attributes such as acidity, alcohol content, pH level, and more.

## Overview

The Wine Quality dataset consists of various physicochemical features of red wines along with a quality score. This project transforms the quality score into a binary classification (Good/Bad) for simplicity. The goal is to predict whether the wine quality is **Good** (score > 6) or **Bad** (score <= 6).

We use a **Random Forest Classifier** to build a machine learning model and evaluate its performance using accuracy, confusion matrix, cross-validation, and feature importance. Hyperparameter optimization is performed using **GridSearchCV** and **RandomizedSearchCV**.

## Table of Contents

- [Requirements](#requirements)
- [Setup](#setup)
- [How to Run](#how-to-run)
- [Model Evaluation](#model-evaluation)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
