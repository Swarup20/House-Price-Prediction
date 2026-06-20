# House Price Prediction

## Project Overview

This project predicts house prices using Machine Learning techniques based on property features such as area, bedrooms, bathrooms, parking, furnishing status, and additional amenities.

The project was completed as part of the XYlofy AI Internship Week 1 Assignment.

## Dataset

Dataset: Housing Prices Dataset

* Total Records: 545
* Features: 13
* Target Variable: Price

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Exploration

* Loaded dataset using Pandas
* Checked dataset shape
* Identified target and feature columns
* Checked missing values

### 2. Data Cleaning

* Removed duplicate records
* Applied One-Hot Encoding to categorical variables
* Prepared data for machine learning

### 3. Model Building

* Linear Regression
* Random Forest Regressor

### 4. Model Evaluation

Metrics used:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

### Results

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.6529   |
| Random Forest     | 0.6119   |

Linear Regression performed better on this dataset.

## Visualizations

* House Price Distribution
* Correlation Heatmap
* Actual vs Predicted Price Comparison

## Key Findings

The most influential factors affecting house prices were:

* Bathrooms
* Air Conditioning
* Hot Water Heating
* Preferred Area
* Stories
* Basement
* Parking

## Project Structure

```
House-Price-Prediction
│
├── analysis.ipynb
├── Housing.csv
├── summary.docx
│
└── Charts
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

## Author

Swarup Karthik S

B.Tech Artificial Intelligence and Data Science
SNS College of Technology
