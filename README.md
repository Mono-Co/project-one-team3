******Stock Market Analysis******

<img width="953" alt="image" src="https://github.com/Mono-Co/project-one-team3/assets/69753431/68cb7d7c-19af-4876-9e9b-caea811b7708">


**Contributors:**

**Ben**

**Dinna**

**Ned**

**Yash**


The primary objective of this project is to perform a comprehensive analysis of the stock market data for companies listed on the Nasdaq stock exchange. We selected six companies, namely, Google: GOOG, Facebook: META, Microsoft: MSFT, MicroStrategy Incorporated: MSTR, Apple: AAPL,and Monday: MNDY. The analysis includes the visualization of historical opening and closing prices, trade volume, and percentage change in opening prices.


**Project Method**

Identifying the coding dependencies, our API to obtain the data was nasdaqdatalinkfrom Nasdaq. Also we incorporated matplotlib.pyplot for creating static plots & statistics for statistical analysis. 
The stock data was initially obtained through the API, and following data cleaning and processing saved as CSV files for for re-importing as Pandas DataFrames. 
To obtain insights into the performance of each stock, a thorough analysis of metrics such as open, high, low, close prices, and trading volume, moving averages was conducted. A historical view of the closing price for all stocks in the company list was generated. Also generated charts & plots are used to visualise and analyse the data.
This project offers insightful information about the stock market performance of the companies chosen from the Nasdaq. Investors can make well-informed decisions about their investing plans by using historical stock price data analysis and key metrics visualization.

<img width="1199" alt="image" src="https://github.com/Mono-Co/project-one-team3/assets/69753431/2cfbc8db-4fac-4beb-8991-363f26757561">



**Project Structure:**

API (Nasdaq Datalink): this is a live data API / Python Module that created tabled directly within a DataFrame, based on the GET query. The NASDAQ DATALINK is based on the QUOTEMEDIA/PRICES request using the NASDAQ API / SDK. (Refer to the NASDAQ documentation for further information).
data: contains CSV files of stock data for each company.
notebooks: Jupyter notebooks for data analysis and visualization.
src: Python scripts for data cleaning, analysis, and visualization.
README.md: Overview of the project and instructions for usage.



**Dependencies:**
** -hvplot.pandas for interactive plotting
** -pandas for data manipulation and analysis
** -pathlib.Path for working with file paths
** -nasdaqdatalink for fetching stock data from the Nasdaq API
** -import numpy as np for numerical computing
** -matplotlib.pyplot for creating static plots
** -statistics for statistical analysis
** -import scipy.stats for statistical analysis
** -scipy.stats for linregress analysis
** -matplotlib.ticker for ticker configuration



**Project Workflow:**

The code is organized into sections, each performing a specific task such as data collection, exploration, visualization, and analysis.
It starts by fetching historical stock price data for multiple companies from the Nasdaq Data Link API using the nasdaqdatalink library.
Data for each stock (GOOG, META, MSFT, MSTR, AAPL, MNDY) is collected, processed, and exported into separate CSV files for further analysis.



**Data Preparation:**

**Two methods were set in place**
We used two main mehtods for bringing date into the project.

<img width="1197" alt="image" src="https://github.com/Mono-Co/project-one-team3/assets/69753431/8958c050-cee7-4b50-be0f-e3d362dd9a7a">



**Method 1**: In case of a paid membership with Nasdaq, use NASDAQ API: (This will require you to skip the import CSV file cells nominated within the Jupyter notebook)

**Method 2**: In case of free membership with Nasdaq datasource, use csv files stored in Resources folder: (This will require you to skip the API Method 1 section and start at the CSV file import cells as nominated within the Jupyter notebook)

The stock data CSV files are imported into Pandas DataFrames.

To maintain consistency and accuracy, the data is carefully cleaned and processed.


**Data Analysis:**

To obtain insights into the performance of each stock, a thorough analysis of metrics such as open, high, low, close prices, and trading volume is conducted.
A historical view of the closing price for all stocks in the company list was generated.


**Data Visualisation:**

The hvplot.pandas and matplotlib.pyplot libraries are used to create both static and interactive charts that show the trend of stock prices and trading volume.
Several data visualization techniques are utilized, including box plots, scatter plots, and line charts.
A script to calculate percentage change in closing price, and outputs the price for a specific company was generated.

Our projects includes visulasiing data as follows:
- Plotting the Closing Price of each company 
- Plotting the Closing Price of each stock on a single Chart
- Creating a new Data Frame for Close Price Mean, Median, Variance and Standard Deviation using the .style funcation. 
- Plotting the Volume of Sales
- Plotting of the distribution of stock Daily Volumen using volume ranges
- Plot 10 days, 20 days, 30 days Moving Average of Stocks 
- Plot percentage of Daily Return of the shares 
- Plot Correlation between recommended stocks closing price and trading volume, including Linear Regression

![Close price for all stocks](https://github.com/Mono-Co/project-one-team3/assets/69753431/6333ef59-35bc-4d07-be71-2dc7acbb77b4)
Close Price for all Stock Visulation.

![volume_ranges](https://github.com/Mono-Co/project-one-team3/assets/69753431/7d0fdd59-ec4a-4b3e-a0c9-4d1ef9e6b4d4)
Stock Daily Trade Volume Range Visulation.

**Statistical Analysis:**

Statistical measures such as percentage change in stock prices are calculated to assess the performance of each stock.



**Usage:**

1.Install all the necessary dependencies are installed in the python environment using 'pip install -r requirements.txt'. This will require a Authentaction to the Nasdaq API. For “nasdaq-data-link” the API Key is noted in the api_config.py file on your local computer files, therefore no API_Config.py file is provided in the GitHub Repository.(Refer to the NASDAQ documentation for further information).

2.Use the supplied Python script to run the stock data extraction and analysis.

3.Export CSV files containing the collected data for further analysis, visualization, and interpretation. The data will be exported to the output_data.

4.Run the Jupyter file Nasdaq_python_Project.ipynb to analyze the stock data.
   
5.Review the generated plots and insights to understand the performance of each stock.



**Conclusion:**

This project offers insightful information about the stock market performance of the six companies listed above that are listed on the Nasdaq exchange. Investors can make well-informed decisions about their investing plans by using historical stock price data analysis and key metrics visualization.



**Acknowledgements:**

Nasdaq Data Link API for providing access to stock data.
Open-source libraries used for data analysis and visualization.



**Feedback:**

Your feedback is highly appreciated! If you have any suggestions, questions, or issues, please create an issue.

<img width="1342" alt="image" src="https://github.com/Mono-Co/project-one-team3/assets/69753431/b1656a29-e343-484d-a635-238ec873b044">


