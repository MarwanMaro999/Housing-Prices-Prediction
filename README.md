# Housing Price Prediction

## Overview
This project focuses on building a machine learning model to predict housing prices based on various features. The dataset includes details such as square footage, number of bedrooms and bathrooms, location, and other relevant attributes. Accurate price predictions are essential for buyers, sellers, and real estate professionals to make informed decisions.

## Features
- Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
- Exploratory Data Analysis (EDA): Understanding feature distributions, correlations, and outliers.
- Model Selection: Evaluating multiple regression models.
- Model Evaluation: Assessing performance using metrics such as RMSE and R-squared.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd housing-price-prediction
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook housing-price.ipynb
   ```
2. Follow the notebook sections to preprocess data, train models, and evaluate performance.

## Dataset
- **Source:** [Provide dataset source if applicable]
- **Features:** Includes numerical and categorical attributes related to housing properties.

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Models

## Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
