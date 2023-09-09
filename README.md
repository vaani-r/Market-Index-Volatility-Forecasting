# Market Index Volatility Forcasting Model
This project was done with Professor Rajan Pandey from BITS Pilani as an exploration of volatility forecasting during an unprecedented financial market.

As a result of the Covid-19 pandemic, India was thrown into a technical recession. To better understand the impact of this event on the stock market, we can reasonably look to the Bombay Stock Exchange's Market Index, known as Sensex, and its volatility. The Sensex is composed of the 30 largest and most actively traded stocks on the exchange and is considered to be one of the broadest market indices in the country. 

For this implementation of a volatility prediction model, we have adopted two types of the Generalized AutoRegressive Conditional Heteroskedasticity (GARCH) Model: Standard GARCH and the GJR-GARCH model. 

## List of Requirements

* arch: https://pypi.org/project/arch/ 
* pandas: https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html

You can download the past n days worth of Sensex data from here: https://www.bseindia.com/Indices/IndexArchiveData.html
Convert the downloaded csv to xlsx if you're facing issues.
