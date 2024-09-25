# Titan Stock Price Prediction using Linear Regression and K-Means Clustering

## Project Overview

This project aims to predict the Titan stock price using two machine learning models:
- **Linear Regression**: A predictive modeling technique to estimate future stock prices based on historical data.
- **K-Means Clustering**: An unsupervised learning method that groups similar stock behavior and helps improve prediction accuracy.

The project also includes Exploratory Data Analysis (EDA), data preprocessing, model evaluation, and stock price prediction.

## Dataset

The dataset used in this project is named `TITAN.csv`, which includes the following features:
- **Date**: The date of the stock entry.
- **Open**: The opening price of the stock.
- **High**: The highest price of the stock for the day.
- **Low**: The lowest price of the stock for the day.
- **Close**: The closing price of the stock.
- **Volume**: The total number of shares traded on that date.

## Project Structure

```
Titan-Stock-Prediction/
├── data/
│   └── TITAN.csv             # The dataset
├── models/
│   └── linear_regression.py   # Linear regression model implementation
│   └── kmeans_clustering.py   # K-means clustering implementation
├── visuals/
│   └── eda_plots.py          # EDA plots and stock price visualization
├── README.md                 # Project documentation
└── requirements.txt          # Required libraries
```

