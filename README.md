# winning-the-market-game
This repository is about how I predict the market, which means developing an algorithm that automatically buys and sells stocks and gets double the S&P500 Indice.
The idea is to have two AI systems working together, the first one is about making predictions (supervised learning) and the second one is about making decisions (reinforcement learning) based on the predictions
 
I'm currently in the development of the first AI system.

The first AI building can be divided into three parts:

# The three main parts:
**First part - getting the data, and arranging it**
The data collection part can be divided into two sections, finding the source of the data and taking it - both made by scraping.
The are not public - using: Scrapy, request, webbroser, javascript, CSS and Xpath

**Second part - preparing the data and EDA**
In this part, we will look at feature engineering and EDA, as well as preparing the dataset for learning.

**Third part - model building, architecture desitions, and training**
In this part, we will train a few models on this data. The main models are XGbost and DL.
The process involves parameter tuning, further EDA (possibly), evaluating and creating pipelines.

the Second AI building can be separated into three parts which are similar to our first part:
 # The three main parts:
**First part - getting the data, and arranging it**
I am evaluating the scraped data with a closed algorithm I built. At the moment this algorithm is modified to generate data based on the idea of investing 100M dollars

**Second part - defining a metric**
This is a secret - the metric is defined

**Third part - model building** 
This part is about training the reinforcement learning.
This part is not ready and will never be public on this repository
