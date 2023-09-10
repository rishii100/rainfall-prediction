# Rainfall Prediction:

This repository contains a Jupyter Notebook for a rainfall prediction project using machine learning. It includes Python code for data preprocessing, model training, and evaluation.

## Table of Contents

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Data](#data)
- [Notebook Explanation](#notebook-explanation)
- [Results](#results)

## Overview

The objective of this project is to predict rainfall based on historical weather data. The Jupyter Notebook includes data loading, preprocessing, model training, and evaluation steps. Three different regression models are used for comparison: `RandomForestRegressor`, `LinearRegression`, and `Lasso`.

## Dependencies

Before running the Jupyter Notebook, ensure you have the following dependencies installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- Jupyter Notebook

You can install these packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/rishii100/rainfall-prediction.git
```

2. Navigate to the project directory:

```bash
cd rainfall-prediction
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open and run the `rainfall.ipynb` notebook.

## Data

The rainfall data is loaded from a CSV file named "rainfall.csv." The dataset contains historical weather data, including monthly rainfall measurements for different subdivisions.

## Notebook Explanation

- `rainfall.ipynb`: This Jupyter Notebook is the main document that performs the following tasks:
  - Loads the dataset using pandas.
  - Cleans and preprocesses the data.
  - Splits the data into training and testing sets.
  - Trains three different regression models: RandomForestRegressor, LinearRegression, and Lasso.
  - Evaluates the models using mean absolute error (MAE).
  - Provides explanations and comments along with the code.

## Result

The results of the model evaluations are as follows:

- RandomForestRegressor: MAE = [MAE Value]
- LinearRegression: MAE = [MAE Value]
- Lasso: MAE = [MAE Value]

The Jupyter Notebook includes visualizations that provide a visual comparison of predicted values, actual values, and absolute errors for the models.
