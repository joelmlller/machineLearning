# Vehicle Price Prediction Project

## Overview

This project focuses on predicting vehicle prices using machine learning techniques. The dataset, sourced from Kaggle, undergoes thorough exploration, cleaning, and visualization before training a Linear Regression model to predict prices.

## Project Structure

The project is structured as follows:

- **Data Cleaning and Exploration**: The dataset is loaded, cleaned, and explored to understand its structure and characteristics.

- **Feature Engineering**: Several columns are dropped, and data types are adjusted for better model predictability. Age of vehicles, based on production year, is calculated, and numeric transformations are applied.

- **Data Visualization**: Various visualizations are created to gain insights into the distribution and features of the dataset.

- **Exploratory Data Analysis (EDA)**: In-depth analysis is performed, revealing patterns and trends in the dataset.

- **Manufacturer Analysis**: Top vehicle manufacturers are identified and analyzed for insights into market trends.

- **Price Analysis**: The relationship between 'Lien' and vehicle prices is explored using scatter plots.

- **Correlation Analysis**: Correlations between numerical features are visualized using heatmaps.

- **Outlier Detection and Treatment**: Outliers in continuous features are identified and addressed to enhance dataset robustness.

- **Data Transformation for Modeling**: Object columns are transformed into numerical format to prepare the dataset for machine learning modeling.

- **Linear Regression Model**: A Linear Regression model is implemented for predicting vehicle prices.

## How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/vehicle-price-prediction.git
   cd vehicle-price-prediction
