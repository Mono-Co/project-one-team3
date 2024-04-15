# Team 3 Project
******Stock Market Review*****

Contributors:
Ben;
Dinna;
Ned;&
Yash:

The primary objective of this project is to perform a comprehensive analysis of the stock market data for companies listed on the Nasdaq stock exchange. We selected six companies, namely, Google: GOOG, Facebook: META, Microsoft: MSFT, MicroStrategy Incorporated: MSTR, Apple: AAPL, Monday: MNDY, Atlassian: TEAM. The analysis includes the visualization of historical opening and closing prices, trade volume, and percentage change in opening prices.

Project Structure:

data: contains CSV files of stock data for each company.
notebooks: Jupyter notebooks for data analysis and visualization.
src: Python scripts for data cleaning, analysis, and visualization.
README.md: Overview of the project and instructions for usage.

Dependencies:

** hvplot.pandas for interactive plotting
** pandas for data manipulation and analysis
** pathlib.Path for working with file paths
** nasdaqdatalink for fetching stock data from the Nasdaq API
**import numpy as np for numerical computing
** matplotlib.pyplot for creating static plots
** statistics for statistical analysis

Project Workflow:

The code is organized into sections, each performing a specific task such as data collection, exploration, visualization, and analysis.
It starts by fetching historical stock price data for multiple companies from the Nasdaq Data Link API using the nasdaqdatalink library.
Data for each stock (GOOG, META, MSFT, MSTR, AAPL, MNDY, TEAM) is collected, processed, and exported into separate CSV files for further analysis.

Data Preparation:
Two methods were set in place;
Method 2: In case of a paid membership with Nasdaq, use NASDAQ API:
Method 2: In case of free membership with Nasdaq datasource, use csv files stored in Resources folder:
The stock data CSV files are imported into Pandas DataFrames.
To maintain consistency and accuracy, the data is carefully cleaned and processed.

Data Analysis:

To obtain insights into the performance of each stock, a thorough analysis of metrics such as open, high, low, close prices, and trading volume is conducted.
A historical view of the closing price for all stocks in the company list was generated.

Data Visualisation:

The hvplot.pandas and matplotlib.pyplot libraries are used to create both static and interactive charts that show the trend of stock prices and trading volume.
Several data visualization techniques are utilized, including box plots, scatter plots, and line charts.
A script to calculate percentage change in closing price, and outputs the price for a specific company was generated

Statistical Analysis:

Statistical measures such as percentage change in stock prices are calculated to assess the performance of each stock.

Usage:

1.Install all the necessary dependencies are installed in the python environment using 'pip install -r requirements.txt'..
2.Use the supplied Python script to run the stock data extraction and analysis.
3.Export CSV files containing the collected data for furthe analysis, visualization, and interpretation. The data will be exported to the output_data.
4. Run the Jupyter file Nasdaq_python_Project.ipynb to analyze the stock data.
5.Review the generated plots and insights to understand the performance of each stock.

Conclusion:

This project offers insightful information about the stock market performance of the six companies listed above that are listed on the Nasdaq exchange. Investors can make well-informed decisions about their investing plans by using historical stock price data analysis and key metrics visualization.

Acknowledgements
Nasdaq Data Link API for providing access to stock data.
Open-source libraries used for data analysis and visualization.

Feedback
Your feedback is highly appreciated! If you have any suggestions, questions, or issues, please create an issue.

