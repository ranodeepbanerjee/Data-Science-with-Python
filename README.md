# Twitter Sentiment Analysis

## Overview

The aim of this project is to predict the sentiment of tweets related to the COVID-19 pandemic as either positive or negative. The dataset used in this project has been pulled from Twitter and manual tagging has been done to categorize the tweets as either positive, negative, neutral, extremely positive, or extremely negative.

# Dependencies

The following libraries are required to run the code:

* numpy
* pandas
* seaborn
* nltk
* sklearn
* matplotlib
* wordcloud

# Classification Models
Three classification models are used to predict the sentiment of tweets: Naive Bayes, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN)


# Results

The output shows that SVM has the highest training accuracy (0.9349) and testing accuracy (0.7722) among the three classifiers. It also has the highest precision, recall, and F1-score in most categories in the classification report.<br>

On the other hand, Naïve Bayes has the lowest accuracy score (0.6849) and KNN has the lowest testing accuracy score (0.3865). Both classifiers also have lower scores in precision, recall, and F1-score in most categories in the classification report compared to SVM.<br>
