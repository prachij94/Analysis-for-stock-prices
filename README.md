# Analysis-for-stock-prices

This repository contains a jupyter notebook on the data analysis about the stock prices of a few banks around the time of the [global financial crisis of 2007-2008](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308) and see how they progressed throughout the financial crisis all the way to early 2016.

The bank stocks considered are:
- Bank of America
- CitiGroup
- Goldman Sachs
- JPMorgan Chase
- Morgan Stanley
- Wells Fargo

The data is read directly from [Yahoo Finance](https://in.finance.yahoo.com/) using Pandas.To derive interesting and meaningful insights from the dataset, data analysis has been performed using Python data exploratory tools like **Pandas** and **Matplotlib, Seaborn, Plotly, Cufflinks for visualization**.

Few of the inferences drawn about the trends in the stock prices from 2006 to 2016 are:

- The max Close price for each bank's stock throughout the time period
- The returns for each bank's stock
- Low returns of Citigroup bank due to Stock crash
- Dates of each bank's stocks with the best and worst single day returns
- The riskiest stock for the entire time period and also for the year 2015
- A line plot showing Close price for each bank for the entire index of time
- Plot of the rolling 30 day average against the Close Price for Bank Of America's stock for the year 2008
- A heatmap and clustermap of the correlation between the stocks Close Price
- A candle plot of Bank of America's stock from Jan 1st 2015 to Jan 1st 2016
- A Simple Moving Averages plot of Morgan Stanley for the year 2015
- A Bollinger Band Plot for Bank of America for the year 2015

# Requirements:
- numpy
- pandas
- datetime
- matplotlib
- seaborn
- plotly
- cufflinks
