# 2020 Election Sentiment Analysis via Tweets and Election Results Prediction
## Overview
Can we predict the results of 2020 election based on public sentiment analysis on social media platforms? In this project, I will conduct sentiment analysis on social media data using natural language processing related to the 2020 election to assess public sentiment. I aim to develop predictive models to forecast state-level voting outcomes based on the observed sentiment trends.

## Background
Every four years, the United States holds presidential elections, which are crucial events that shape the country's political landscape. Understanding public sentiment and opinion towards presidential candidates is essential for political analysts, policymakers, and the general public. Social media platforms have emerged as powerful tools for gauging public sentiment in near real-time.

## Objective
The objective of this project is to analyze public sentiment towards the 2020 US election and attempt the predict which candidate each state will vote for based on public sentiment gathered from Twitter. The project aims to:
* Explore the data graphically to gain a better understanding of the distribution of where the tweets came from
* Utilize natural language processing techniques to analyze and interpret the sentiment of social media posts
* Attempt to predict which candidate a state will vote for, and the overall winner of the 2020 election.

## Data Sources
The data used here was obtained from Kaggle [here](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets). It was obtained through the Twitter API and is split into two datasets, one for tweets pertaining to Joe Biden, and another for tweets pertaining to Donald Trump. This tweets were collected from the beginning of 2020 to 11/8/2020, one day before election day.

## Methods
This project will utilize the following methods:
* Data preprocessing: Clean and preprocess the data, removing unnecessary characters, columns, and row entries that do not pertain to the study.
* Exploratory data analysis: Visualize the data and the distribution of where the tweets originate from, and which presidential is talked about where.
* Sentiment analysis: Utilize natural language processing techniques to analyze the sentiment of the tweets towards the presidential candidates.

## Results
Our results determined that Joe Biden would be the winner, and we can see in our final results that while the margin for him winning was smaller than anticipated, our predictions were not far off. This project provided valuable insights into public opinion and sentiment surrounding the 2020 US presidential election, and can provide even further insight into the upcoming 2024 presidential election. By leveraging social media data and natural language processing techniques, this project enhances our understanding of political discourse.

## Future Work
This project has a few ways it can be improved upon in the future. 
  * Utilizing a stronger sentiment analyzer tool. In this project, I used TextBlob. While it is a sufficient sentiment analyzer tool, there are stronger ones available, like the Transformer tool roBERTa, which has been trained in 52+ million tweets to analyze their sentiment. However, it is incredibly resource intensive and compututationally expensive, and while I attempted to run it on my puny Macbook Air, it took approximately 17 hours before it errored out.
  * Incorporating other social media platforms. While Twitter was at its height during the 2020 election, with a recent change in CEO, it has dropped in its discussion. For replicating this project, I recommend utilizing Facebook's (or Meta's) API or even the TikTok API to gain a better understanding of where public sentiment stands.
