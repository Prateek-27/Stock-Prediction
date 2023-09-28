# Stock Price Prediction using Numerical and Textual Analysis

This repository contains code for predicting stock prices of TCS (Tata Consultancy Services) using numerical data (stock prices) and textual data (news headlines). The model utilizes both numerical and textual analysis to enhance the accuracy of the predictions.

## Files
- `StockPrediction.ipynb`: Jupyter Notebook containing the code for stock prediction, from data preprocessing to modeling.
- `india-news-headlines.csv`: CSV file containing headlines data used for textual analysis.
- `TCS.csv`: CSV file containing TCS stock data for numerical analysis.

## Dependencies
- pandas
- numpy
- matplotlib
- textblob
- sklearn

## Features

- **Data Preprocessing:**
  - Handles missing values in the dataset.
  - The `Date` feature is converted into a format suitable for analysis, and additional time features can be engineered as needed.

- **Textual Analysis:**
  - Calculates polarity scores for news headlines using the TextBlob library.
  - The code can be easily extended to include other NLP techniques or sentiment analysis metrics.

- **Modeling:**
  - Uses `SGDRegressor` and `RandomForestRegressor` from the sklearn library for prediction.
  - The framework allows for easy experimentation with other regression models and hyperparameter tuning.

- **Evaluation:**
  - Prints the accuracy of the models and can be extended to include more evaluation metrics and visualization plots.

## Conclusion
I compared two machine learning algorithms, namely Stochastic Gradient Descent and Random Forest, and was able to predict the closing stock prices for the TCS dataset using the model that gave a higher accuracy which was the Random Forest Algorithm with an accuracy of 99.95%. Apart from the stock data, I used the news headlines data to find the sentiment and used that sentiment analysis for a better prediction.
