# Grimoire
>[!IMPORTANT]
>### What is this?

HTML page that allows you to keep track of what a bitcoin price will be in an hour.<br/>
Uses BINANCE spot btc/usdt data.<br/>
Predictions have high success rate (75%) and low margin of error (± 0.4%).<br/>
Stable with the exception of 'black swan' events.<br/>

>[!NOTE]
>### How does this work?

First fresh hourly data is fetched from binance api. <br/>
Then prognosis is made based on that data using one of the simplest methods - 'percentile fork'.<br/>
Percentiles used in calculation are based on binance BTC/USDT klines spot historical data starting from year 2017 and up to modern days.<br/>
You can find the aforementioned data here: https://data.binance.vision <br/>
Percentiles remain stable for half a year minimum.<br/>

> [!TIP]
>### Find out what the price of bitcoin will be: https://vadimvn.github.io/grimoire/
