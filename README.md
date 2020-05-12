# Profitable-APP-Store
Profitable App Profiles for the App Store and Google Play Markets

# Project 1 - DataQuest - Introduction to Python

## Cleanning Data

For this project, I'm going to work as data analysts for a company that builds Android and iOS mobile apps. 

The goal is to analyze data to help our developers understand what type of apps are likely to attract more users.
To do this, I'll need to collect and analyze data about mobile apps available on Google Play and the App Store.

Collecting data for over 4 million apps requires a significant amount of time and money.

> Number of apps available in leading app stores as of 3rd quarter 2019  ([Link](https://www.statista.com/statistics/276623/number-of-apps-available-in-leading-app-stores/))

![Stat](https://github.com/sandramalaquias/Profitable-APP-Store/blob/master/index.png)

To avoid spending resources on collecting new data ourselves, I should first try to see if I can find any relevant existing data at no cost. Luckily, these are two data sets that seem suitable for my goals (both find in Kaggle):


* A **data set** containing data about approximately 10,000 Android apps from Google Play; the data was collected in August 2018. You can download the data set directly from this [link](https://www.kaggle.com/lava18/google-play-store-apps).
* A **data set** containing data about approximately 7,000 iOS apps from the App Store; the data was collected in July 2017. You can download the data set directly from this [link](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps).

Note that for this exercise I'm using only a Python command and has addcional notes clarifying the steps used and why. It is  divided in two pars:
  * clean the datas set and write a new one
  * analyse and get the insights
  
## Clean the Data
The main challenge for this exercise is to work with a "Codecs" and "RE" libraries to identify Asia characteres and drop them from the files. The addicional resourse are:
  * "PrintTable" library to easier way for data visualization.
  * "Operator" library to Sort command
  * "Copy" libraty to create a free list
  
 ## Analyse Data
 To minimize risks and overhead, our validation strategy for an app idea is comprised of three steps:

    Build a minimal Android version of the app, and add it to Google Play.
    If the app has a good response from users, we develop it further.
    If the app is profitable after six months, we build an iOS version of the app and add it to the App Store.

Because our end goal is to add the app on both Google Play and the App Store, we need to find app profiles that are successful on both markets. For instance, a profile that works well for both markets might be a productivity app that makes use of gamification. For this analysis, no make sense to built a message exchange app.

In this part of project have many observation until arrive a conclusion, as follow.

## Conclusions

In this project, we analyzed data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can be profitable for both markets.

We concluded that taking a popular book (perhaps a more recent book) and turning it into an app could be profitable for both the Google Play and the App Store markets. The markets are already full of libraries, so we need to add some special features besides the raw version of the book. This might include daily quotes from the book, an audio version of the book, quizzes on the book, a forum where people can discuss the book, etc.


