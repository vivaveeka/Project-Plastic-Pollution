
# Final Project | Plastic Pollution Reach

## Introduction

The goal of this project is to apply all data analytics concepts that I have learned during 10-weeks of the bootcamp to a real-world data project. Up to this point I learned the following data analytics concepts:

- Data wrangling and cleaning with pandas
- API and web scraping
- Intermediate topics in Git, MySQL, and Python
- Data analysis using Pandas 
- Statistics & probability
- Exploratory data visual
- Storytelling through data visualization, business intelligence
- Machine learning: basics
- Scikit-learn
- Applied machine learning 


## Project Description

This project looks into twitter accounts that are advocating for plastic pollution prevention and cleanup and trying to measure the reach of people in reducing the plastic footprint. The idea is to analyze plastic pollution subject matter channels on twitter for 30 or so twitter accounts going back and analyzing specific number of tweets (about 3200 tweets) as per permission of the twitter API.

The questions I am trying to answer are: 

1) Are certain tweets more successful in terms of reach?
2) Are specific words more powerful than others?


## Task

The task was to analyze around 30 twitter accounts that are involved in plastic pollution prevention and/or cleanup. I had to use twitter API key and extract the maximum number of tweets for each account (around 3200 tweets). Next, I had to determine the number of followers for each account and then figure out how to create and calculate a score for each account. Next, I was to complete word analysis using natural language processing.


## Action

Tools Used:
API
Python
Jupyter Notebook
Tableau

Skills Used:
Data Cleaning
Data Retrieval
Data Analysis
Data visualisation
Applied machine learning: NLP

Steps Followed:
1) I used twitter API key to obtain anywhere from 2000-3200 (depended on the account) tweets going back from 3rd quarter 2020 all the way to the 4th quarter 2009 for the chosen 29 accounts with a final total of 85,000 tweets.
2) I calculated 'estimated_followers' for each account per quarter using 'way back machine’ internet archive. 
3) I wanted to normalize data agaist average tweet counts, so I created and calculated 'absolute_reach' score which consists of sum of the number of retweets plus favorite count (favorite count is divided by two) for each account.
4) I then wanted to normalize the size of the network, thus I calculated 'relative_reach' score which is 'absolute_reach' score divided by 'estimated_followers'. The normalization is linear and to make data more intuitive I multiplied this score by 1,000,000. 


## Result

I obtained the following results 

A link to my public tableau with project's graphs

https://public.tableau.com/profile/viktoriya.shirochenkova#!/vizhome/TwitterPlasticPollutionReach/TF-IDFRatioAllWords

