<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Bitcon time series forecasting

This dataset based on<sup>1</sup> contains time series forecasting of BitCoin values.

The data can be used to build and train an ML model that can make a regresion using time series forecasting techniques. 

This use case show how to employ basically LSTM component to time series forecasting. It's not improved and only use 10 previous days to forecasting, that is not enough but show how to use Perceptilabs software in a use case of time series forecast.

# Structure

This repo contains the following structure:

- **BT-USD-TimeSeries.csv**: CSV file with time series data of BitCoin.


The following shows a partial example of the data stored in **BT-USD-TimeSeries.csv* that is used to load the data into PerceptiLabs. Where each column is a day, and last column is the target. All values are normalized between 0 and 1 that is a requirement for LSTM layers.

<p align="center">
  <img src="./sample.png">
</p>


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://finance.yahoo.com/quote/BTC-USD/history/
