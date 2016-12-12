# Data Mining and Sentiment Analysis using StockTwits

## Introduction
Predicting stock market performance is big business. However, most models are incomplete as they have been unable to take social influence into account. Mining social media for insight into the sentiment of stock traders and investors has the potential to lead to a more-complete understanding of stocks performance. In this project, we elected to focus on predicting sentiment of traders and investors.

[StockTwits](http://stocktwits.com/) is a social-media platform similar to Twitter aimed at stock traders and investors. Instead of hashtags, StockTwits has stock ticker tags like **\$AMD** or **\$AAPL** that users post in their twits. In addition, tweets can be tagged with 'bullish' or 'bearish' to indicate if the poster thinks the mentioned stocks will move upwards or downwards in price. This is in fact pre-labelled training set.

We conducted several analyses using this data:
* Mined StockTwits for data and combine it with Stock Financial history.
* Visualized metrics from both StockTwits and the Stock Market to gain intuition on their possible relationship.
* Reviewed bullish/bearish tags of specific companies and their correlation with the movement of the actual stock price or trading volume.
* Implemented sentiment analysis on specific companies.

Ultimately, we decided to focus on sentiment analysis. Though there is much excitement in predicting stock performance from tweets, we do not feel that we have sufficient data to support that claim at this time. Accurate sentiment analysis of tweets will be an important step in reaching that conclusion, if possible.

## Prior Work
StockTwits provides [several whitepapers](http://stocktwits.com/developers/docs/research) on previous experiments conducted using their service. In particular, *[On the Predictability of Stock Market Behavior
using StockTwits Sentiment and Posting Volume](http://stocktwits.com/research/Predictability-of-stock-market-behavior-using-stocktwits-sentiment-and-posting-volume_NunoOliveira.pdf)* were useful templates for this project.
