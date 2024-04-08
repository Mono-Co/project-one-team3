# Team 3 Project
******Stock Market Review*****

Team Members:

We have the following team members:
Ben;
Dinna;
Ned;&
Yash:

The primary objective of this project is to perform a comprehensive analysis of the stock market data for companies listed on the Nasdaq stock exchange. We selected seven companies, namely, Google: GOOG, Facebook: META, Microsoft: MSFT, MicroStrategy Incorporated: MSTR, Apple: AAPL, Monday: MNDY, Atlassian: TEAM. 

Dependencies:

** hvplot.pandas for interactive plotting
** pandas for data manipulation and analysis
** requests for making HTTP requests to fetch data
** json for working with JSON data
** pathlib.Path for working with file paths
** nasdaqdatalink for fetching stock data from the Nasdaq API
** matplotlib.pyplot for creating static plots
** statistics for statistical analysis

Project Workflow:

The project starts by fetching historical stock price data for multiple companies from the Nasdaq Data Link API using the nasdaqdatalink library.
The fetched data is stored in CSV files for further processing.

Data Preparation:

The stock data CSV files are imported into Pandas DataFrames.
To maintain consistency and accuracy, the data is carefully cleaned and processed.

Data Analysis:

To obtain insights into the performance of each stock, a thorough analysis of metrics such as open, high, low, close prices, and trading volume is conducted.

Data Visualisation:

The hvplot.pandas and matplotlib.pyplot libraries are used to create both static and interactive charts that show the trend of stock prices and trading volume.
Several data visualization techniques are utilized, including histograms, scatter plots, and line charts.

Statistical Analysis:

Statistical measures such as percentage change in stock prices are calculated to assess the performance of each stock.

Usage:

Install all the necessary dependencies are installed in the python environment.
Use the supplied Python script to run the stock data extraction and analysis.
Review the generated plots and insights to understand the performance of each stock.

Conclusion:

This project provides valuable insights on how various companies listed on the Nasdaq exchange are performing in the stock market. Investors can use historical stock price data analysis and visualization of key metrics to make well-informed decisions regarding their investment strategies.
