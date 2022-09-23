# Cryptocurrency Data Analysis

# Dataset Overview

In this end-to-end project, the dataset contains cryptocurrencies live data that was scrapped from [Cryptowatch](https://cryptowat.ch/), a popular charting & trading terminal for cryptocurrency markets. This market data is solely about the Crypto market transaction done on the Binance Exchange platform.

The goal of this project is to analyze the market trends and movements of **top 10 cryptocurrencies for the past four years**, starting from 1st September 2018 (2018-09-01) to 5th September 2022 (2022-09-05).

The dataset consists of 27,585 rows and 9 columns in total. The columns include CloseTime, OpenPrice, HighPrice, LowPrice, ClosePrice, volume, MarketCap, Symbol, and Name. 6 of the features are in a string (object) data type while three were in a float data type.

# Metadata

The dataset columns include:

 - CloseTime: This refers to the particular date and time of a specific market movement of a coin. From this column, we extracted the date, year, and month columns.
 
 - ClosePrice: The Closing price of a coin within a 24-hr time frame.

 - OpenPrice: The Opening price of a coin within a 24-hr time frame.

 - HighPrice: The highest price of a coin within the same 24-hour time limit.
 
 - LowPrice: The lowest price of a coin within the same 24-hour time limit.
 
 - volume: the number of coins traded within a day; 24 hours.
 
 - MarketCap: the crypto market cap is the market value of a cryptocurrency. It's derived by multiplying the total number of mined cryptos and the prevailing market price. Since the number of mined cryptos and market price keeps changing, the crypto market cap also keeps fluctuating. Market Cap = supply x price.
 
 - Symbol: The symbol of each cryptocurrency.
 
- Name: Name of each  cryptocurrency.

 - The Datetime Column was changed from object to dataetime data type.

# Summary of Findings

After the dataset was wrangled and analyzed thoroughly, I found the following insights:
At the time of the analysis, 

 - As of 5th September 2022, on that particular day, Ripple (XRP) had the highest percentage market cap value which is about 4.840165M% followed by Bitcoin (BTC) and Ethereum (ETH) whose percentage change of market price value is about 3.903218M% and 2.866002M% respectively.
 
 - Bitcoin's (BTC) Close price has always been the highest that which makes the high price of other cryptocurrencies invincible. Ethereum (ETH), Cardona (ADA), and Polygon (MATIC) also showed high Close Prices when compared with other cryptocurrencies that were selected. The graph shows that BTC and ETH had high values for the past four years.
 
- With a candlestick chart, there has been a symmetric pattern in the different crypto coin prices for the past four years, and this is said to happen when buyers and sellers become indecisive about the market. There were bullish and bearish trends at different points in time, and the volumes of the coins were seen to drop over time due to this pattern.

 - The USDT market trend is very volatile and should be avoided as much as possible. It's not so clear when you should buy and sell in that market.
 
 - The Moving averages of coins against their Close Prices show that the Bitcoin market is currently neither bullish nor bearish, while ETC and MATIC markets show a bullish trend which indicates a good time to trade on those coins.

# Dashboard Report

Here’s a link to a [Dashboard Report](https://www.novypro.com/project/cryptocurrency-data-analysis) I created at the end of this project. It is an interactive report where I utilized the built-in predictive forecasting models in Power BI to forecast future market trends of the selected cryptocurrencies based on 95% confidence values within the next 12 months.

You can also read my [blog](https://medium.com/@chisompromise/the-world-of-digital-assets-cryptocurrency-data-analysis-5a31112945ef)post on this project.
