# clever-meme

## Introduction
A quantitative trading tutorial based on TradingView, including detailed explanations and implementation processes of technical indicators, quantitative strategy implementation, backtesting methods, live trading verification, and legends in the trading world. Continuously updating~~~

----------------------------------
## Project Sections
----------------------------------
### 1. Indicators
#### 1.1 Basic Indicators for Quantitative Trading
Technical indicators are excellent collections summarized by countless great traders over the years, which you can find on major trading platforms. I will reproduce the implementation process of these indicators on TradingView. This part aims to solidify the foundation, helping you understand the essence of trading, find certain potential patterns from so-called time series, and achieve simple predictions to judge future trends.

At the same time, it serves as a starting point, as most complex indicators are derived from combinations of these basic indicators. You can directly modify these basic codes or refactor them according to your needs.

##### 1.1.1 MACD
MACD is known as the king of technical indicators. Detailed information about the MACD indicator (Moving Average Convergence Divergence) can be found in [MACD](Quant-code/indicator/MACD.md).

Including calculation methods, derived indicators, application scenarios, advantages and disadvantages, etc.

##### 1.1.2 RSI
Detailed information about the RSI indicator (Relative Strength Index) can be found in [RSI](Quant-code/indicator/RSI.md).

Including calculation methods, derived indicators, application scenarios, advantages and disadvantages, etc.

Additionally, a novel RSI-derived indicator is attached. Specific usage examples can be found in [RSI](Quant-code/indicator/RSI.md), and the original code can be directly referenced in [Parabolic RSI](Quant-code/indicator/抛物线RSI.pine).

##### 1.1.3 KDJ
All information about the KDJ indicator (Stochastic Oscillator) can be found in [KDJ](Quant-code/indicator/KDJ.md).

##### 1.2 Advanced Indicators for Quantitative Trading
From simple to complex, gradually introduce commonly used advanced indicators in quantitative trading.
##### 1.2.1 Bollinger Bands
The principle of Bollinger Bands is to determine the volatility range of prices by calculating the average and standard deviation of prices, thereby identifying high and low prices.

Detailed information about the Bollinger Bands indicator can be found in [Bollinger Bands](Quant-code/indicator/Bollinger-Bands.md).

##### 1.2.2 Donchian Channel

----------------------------------
### 2. Strategies
#### 2.1 Those Evergreen Classic Strategies

##### 2.1.1 Dual Moving Average Strategy

##### 2.1.2 Turtle Strategy


#### 2.2 The Secret Recipes of Genius Quantitative Traders -- Those Imaginative Trading Strategies

##### 2.2.1 Buu Quant - Pin Strategy

This is an interesting strategy I encountered. In the cryptocurrency market, during volatile periods in ranging markets, pin bars appear in short-term operations. You can try to precisely enter at the lowest/highest points and profit when the volatility returns to normal levels.

Specific introduction can be found in [Buu Quant - Pin Strategy](Quant-code/strategy/布欧量化-接针策略.md).

#### 2.3 Contract and Grid Trading
Contract grid is a quantitative trading strategy used for automatic buying and selling of futures contracts. The contract grid bot can automatically place orders in the market at preset intervals within a set price range.

In grid trading, the system automatically places orders above or below the set price, forming an incremental and decremental grid of orders. In this way, a complete trading grid can be constructed. For example, traders can place BTC buy orders below the market price and BTC sell orders above the market price in units of 1,000 USDT, profiting from range-bound market conditions.

Grid trading strategies perform best when the market is volatile and consolidating, with prices fluctuating within a given range. This strategy aims to profit from small price fluctuations. The more grids there are, the higher the trading frequency, but the lower the profit per order.

Therefore, traders need to choose between high-frequency small profits and low-frequency large profits as needed.

Detailed introduction and usage methods of contract grid can be found on Binance's website. [Binance - Introduction to Contract Grid Trading](https://www.binance.com/en/support/faq/detail/f4c453bab89648beb722aa26634120c3)

---------------------------------
### 3. Backtest
---------------------------------
### 4. Live Trading
---------------------------------
### 5. Talks & Trading Legends
#### 5.1 Livermore

#### 5.2 Buffett
---------------------------------
## Contributing

1.  Fork this repository
2.  Create a new Feat_xxx branch
3.  Commit your code
4.  Create a new Pull Request


## Features

1.  Use Readme_XXX.md to support different languages, such as Readme_en.md, Readme_zh.md
2.  Gitee official blog [blog.gitee.com](https://blog.gitee.com)
3.  You can visit [https://gitee.com/explore](https://gitee.com/explore) to learn about excellent open-source projects on Gitee
4.  [GVP](https://gitee.com/gvp) stands for Gitee Most Valuable Open Source Project, which is an excellent open-source project comprehensively evaluated
5.  Gitee official user manual [https://gitee.com/help](https://gitee.com/help)
6.  Gitee Cover is a column to showcase the style of Gitee members [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)