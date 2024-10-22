# HousePricePrediction
# California Housing Price Prediction

This project focuses on predicting median house prices in California using machine learning. It includes data preprocessing, visualization, and the creation of two different regression models.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Code](#code)
- [Visualizations](#visualizations)
- [Models](#models)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to predict median house prices in California based on various features. It involves data preprocessing, visualization, and the creation of two regression models: Linear Regression and Decision Tree Regression.

## Dataset

The dataset used in this project is the "California Housing Prices" dataset. It contains various attributes related to housing in different districts of California.

- **Data Source**: [California Housing Prices Dataset](https://github.com/Abhishek0145/HousePricePrediction/blob/main/california_housing.csv)

## Code

The code for this project is written in Python and is divided into several sections:

- Data loading and exploration
- Data preprocessing
- Visualization of data
- Model building and evaluation
- Linear Regression and Decision Tree Regression

## Visualizations

To better understand the dataset and relationships between features, visualizations have been included in the code:

- Histogram of the distribution of 'median_house_value'.
- Correlation heatmap to visualize relationships between features.
-  **Residual Plot for Linear Regression**: A plot showing the residuals (difference between predicted and actual values) for the Linear Regression model.

## Models

Two regression models are implemented in this project:

1. **Linear Regression**: A simple linear regression model is built to predict house prices.
2. **Decision Tree Regression**: A decision tree-based regression model is used to make predictions.

The performance of these models is evaluated using R-squared scores on both training and testing data.

## Usage

To run the code and reproduce the results:

1. Clone this repository.
2. Ensure you have the required Python libraries installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Download the dataset from [here](https://github.com/Abhishek0145/HousePricePrediction/blob/main/california_housing.csv) and place it in the project directory.
4. Run the Jupyter Notebook or Python script to execute the code.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request describing your changes.
