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

## Project Steps

## 1. Exploratory Data Analysis (EDA)

- The dataset is analyzed to understand stock trends, missing values, and correlations between features.

- Stock price trends over time are visualized using line plots.

## 2. Data Preprocessing

- The ```Date``` column is converted to a datetime format and set as the index.

- Missing values are handled, and relevant features are selected for modeling.

- The dataset is split into training and testing sets.

## 3. Linear Regression Model

- A linear regression model is trained to predict the stock's closing price based on the features.

- The model is evaluated using Mean Squared Error (MSE) and R2 score metrics.

- A stock price analysis chart is generated to compare actual vs. predicted values.

## 4. K-Means Clustering

- The dataset is scaled, and K-means clustering is applied to group the stock behavior.

- The elbow method is used to find the optimal number of clusters.

- The clusters are visualized to understand stock price patterns.

## 5. Predicting Stock Price with Clustered Data

- A new Linear Regression model is trained using clustered data to predict stock prices.

- The model is evaluated using MSE and R2 score, and results are compared with the original regression model.

## How to Run the Project

1. **Clone the repository**:

   ```
   git clone https://github.com/yourusername/Titan-Stock-Prediction.git
   cd Titan-Stock-Prediction
   ```

2. **Install required libraries**: Make sure you have Python installed. Install the necessary dependencies using:

   ```
   pip install -r requirements.txt
   ```

3. **Run the models**: To run the Linear Regression and K-Means Clustering models, execute:

    ```
    python models/linear_regression.py
    python models/kmeans_clustering.py
    ```

4. **View the results**:

 - Results, such as actual vs predicted stock prices, MSE, and R2 scores, will be displayed on the console.

- Stock price trends and cluster visualizations will be generated in the form of charts.

## Results

- **Linear Regression**:

  - The linear regression model achieves an R2 score of ```X.XX``` and a Mean Squared Error of ```Y.YY```.

  - The predicted stock prices are visually close to actual stock prices.

- **K-Means Clustering**:

  - K-Means clustering helped group the stock data into ```k``` clusters, improving the predictive performance.

  - The R2 score after clustering improved to ```Z.ZZ```, with a Mean Squared Error of ```W.WW```.

## Conclusion

This project demonstrates how both supervised and unsupervised learning techniques can be applied to stock price prediction. By leveraging clustering, we are able to improve the accuracy of the model, and the visualizations provide better insights into the stock behavior.

## Future Work

- Incorporate other machine learning models (e.g., Decision Trees, Random Forest).

- Apply feature engineering to enhance prediction accuracy.

- Use more advanced time-series prediction models such as ARIMA or LSTM.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
