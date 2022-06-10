# Preprocessing-Clustering-Predict-stock-data-by-TimeSeriKmean-using-python
Language: Python

Environment: Google colab or Jupyter notebook.

Requirement:
- Apply crawling techniques from 100 stocks. Collect daily stock prices (close prices) of those tickers for the years 2020, 2021, 2022 from any website.
- Normalize the data using TimeSeriesScalerMeanVariance or other methods. This scales so that each output time series has no mean and unit variance. 
Displays an image that includes the daily price and an image that includes the daily price after normalization of 5 stock symbols.
- Use the k-means timeseries method with three methods to group the daily stock prices of those stock symbols. For each variation, use the elbow method 
to choose the best k. The gray line is the stock price movement within each cluster. The red line is the center line of the gray lines in each cluster.
- Pick a stock label, use the stock prices in 2020 and 2021 to train any predictive method. Then use the trained model to predict the stock price for the 
first 4 months in 2022.
