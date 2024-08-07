# Car Price Prediction Analysis

## Overview

This repository contains a Python-based solution for predicting car prices using machine learning techniques. The analysis includes data exploration, visualization, and predictive modeling with Linear Regression and Random Forest algorithms.

## Features

- **Data Exploration**: Loads and explores the dataset, handles missing values, and examines the distribution of different features.
- **Visualization**: Generates plots to visualize categorical distributions, numerical feature relationships, and feature-target relationships.
- **Predictive Modeling**: Trains and evaluates Linear Regression and Random Forest models to predict car selling prices.
- **Model Evaluation**: Assesses model performance using Root Mean Squared Error (RMSE) metrics.

## Prerequisites

Make sure you have the following Python packages installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the necessary packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Usage
Load and Explore Data: The script reads the car dataset from a specified file path and performs initial exploration and visualization.

Visualization: The script generates various plots to understand feature distributions and relationships between features and the target variable (Selling Price).

Model Training:

Linear Regression: Trains a Linear Regression model and evaluates its performance using RMSE.
Random Forest: Trains a Random Forest Regressor and evaluates its performance using RMSE.
Run the Script: Execute the script using Python:
python car_price_prediction.py
