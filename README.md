# Monte Carlo Stock Forecasting Project

This repository contains implementations of stock forecasting models and strategies in Python. The project is organized into the following folders:

1. **MonteCarlo**
   - `Price_Paths.ipynb`: Contains the introductory project to first calculate the daily price changes using the geometric Brownian motion formula, then compute the price at each time step based on the previous price and the corresponding daily return.
     
   - `MC_Functions.ipynb`: This folder contains a comprehensive set of Python functions to simulate stock prices and analyze their performance using Monte Carlo methods. The primary objective is to forecast future prices and evaluate    key metrics like beta, Sharpe ratio, and CAPM return. <br/>

   The code includes functions to download historical stock data using yfinance, compute daily log and simple returns, and calculate the drift component representing expected returns. The Geometric Brownian Motion (GBM) model is used to generate daily returns, incorporating drift and volatility. Additional functions combine stock data with market index data to calculate annualized returns, and compute CAPM metrics such as beta and Sharpe ratio to evaluate stock performance against the market.

   The simulation component generates multiple price paths over a specified number of days and iterations, visualizes results, and calculates the probability of stock prices exceeding specified values or return rates. The monte_carlo function loops through a list of stock tickers, runs simulations, and outputs key metrics. Users can simulate future stock prices and compute performance metrics by specifying parameters such as tickers, forecast period, number of iterations, and start date.
   
   - `MC_Main.py`: Contains the implementation of the above Monte Carlo functions in order to analyze simulated price paths, key performance metrics, and plots showing the distribution and cumulative distribution of simulated prices, providing valuable insights for investment decision-making.

   The Monte Carlo forecast uses random sampling techniques to simulate various future scenarios based on historical data. Project followed: https://medium.com/analytics-vidhya/monte-carlo-simulations-for-predicting-stock-prices-python-a64f53585662


3. **Least Squares Monte Carlo**
