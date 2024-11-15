# Stock Analysis Project

## Project Goal

The goal of this project is to analyze the stock performance based on posts from Reddit's WallStreetBets and Stocks subreddits. By leveraging sentiment analysis and historical stock data, we aim to understand the impact of social media discussions on stock prices.

## High-Level Overview

### getRedditPosts

This module is responsible for fetching posts from the WallStreetBets and Stocks subreddits. It utilizes the Reddit API to gather the latest discussions, which are then stored for further analysis. The focus is on capturing posts with high engagement, as these are more likely to influence stock movements.

### cleanRedditPosts

Once the Reddit posts are fetched, this module processes and cleans the data. It removes unnecessary information, filters out irrelevant content, and prepares the text for sentiment analysis. The goal is to ensure that the data is in a consistent format, making it easier to extract meaningful insights.

### analyzeRedditPosts

This module performs sentiment analysis on the cleaned Reddit posts. It evaluates the overall sentiment of the discussions and correlates it with historical stock prices. By doing so, it attempts to measure the potential impact of Reddit discussions on stock performance, providing valuable insights for investors and analysts.