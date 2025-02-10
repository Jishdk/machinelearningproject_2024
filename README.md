# Dutch Housing Price Prediction Project

This project implements machine learning models to predict house prices in the Netherlands using property characteristics. It follows a complete data science approach from data exploration to model evaluation.

## Project Structure

housing_price_prediction/
├── data/
│   └── raw_data.csv               # Original Dutch housing dataset
├── notebooks/
│   ├── 1_data_exploration.ipynb   # Initial data analysis and visualization
│   ├── 2_data_preprocessing.ipynb # Feature engineering and data preparation
│   └── 3_model_development.ipynb  # Model training and evaluation
├── preprocessed_data/             # Stores processed datasets
└── README.md                      # This file

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Required Python packages (install using requirements.txt)

### Installation
1. Clone this repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install required packages
pip install -r requirements.txt

Running the Project

Start with data_exploration.ipynb to understand the dataset
Run data_preprocessing.ipynb to prepare data for modeling
Execute model_development.ipynb to train and evaluate models

### Notebooks Description

1. Data Exploration

Initial data analysis
Feature distributions
Correlation analysis
Data quality assessment

2. Data Preprocessing

Data cleaning
Feature engineering
Handling missing values
Feature encoding
Train/validation/test split

3. Model Development

Model implementation (Linear Regression, KNN, Decision Tree, Random Forest)
Hyperparameter tuning
Model evaluation
Performance comparison

Dataset
The dataset contains information about Dutch houses including:

Living space size
Lot size
Build year
House type
City
Energy label
Price (target variable)

Source: Funda.nl (Dutch real estate website)
Models Implemented

Linear Regression (baseline)
K-Nearest Neighbors
Decision Tree
Random Forest

Results
Model performance is evaluated using:

Root Mean Square Error (RMSE)
Mean Absolute Error (MAE)
R-squared (R²)

## Author
Jishnu Harinandansingh
852768738

## Acknowledgments

Open Universiteit Machine Learning Course
Dataset creator: Bryan Lusse
https://www.kaggle.com/datasets/bryan2k19/dutch-house-prices-dataset/data
https://github.com/bryanlusse/HousePrices__Webscraper?tab=readme-ov-file#chart_with_upwards_trend-model
