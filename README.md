# Crypto Signals Data Replication Package

This contains scripts to collect and analyze crypto signals data on  X (formerly Twitter) to understand the impact of crypto signals on users. Descriptions of the folder contents with the paper sections are provided below:

## Data Collection

* TweetingCryptoAnalysisDataset.xlsx: Dataset containing the X crypto signal data of popular crypto-related tweets, cryptocurrency value metrics for before and after signals, and data regarding the replies to crypto signal posts (Tweets Replies Data tab).

* replies.py: Script to collect the comments replying from users on crypto signals in our dataset.

## Data Analysis

* twitter_sentiment_analysis.py: Python script to perform the sentiment analysis on replies data with the natural language toolkit sentiment analyzer.

