# Amazon-fine-food-review-NLP
Sentiment analysis, BOW, TFIDIF,W2V,Naïve Bayes,XGboost,Logistic Regression

In this project we have worked on 4 kernals, below are the details:

1)Amazon fine food review - Sentiment analysis: In this notebook we have attempted two prediction. 1) Score prediction -where we predict the score given the comments using various NLP technique like BOW,TFIDF,TFIDF + ngram, 2)Upvote prediction -where we predict the number of upvote  given the comments using various NLP technique like BOW,TFIDF,TFIDF + ngram.

2)Amazon_fine-food-reviews:- In this notebook we have extensively done EDA and feature engineering. We tried to understand the significance of wordcloud , BOW, TFIDF, W2V .

3)Amazon_fine-food-reviews_v2:Here we have predicted the score using Naive Bayes, LR and XGboost after extensive feature engineering.

4)Text Classification using SpaCy:- We have explored spacy.

Description:

Context
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Contents
Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite
database.sqlite: Contains the table 'Reviews'

Data includes:

Reviews from Oct 1999 - Oct 2012
568,454 reviews
256,059 users
74,258 products
260 users with > 50 reviews
wordcloud

Acknowledgements
See this SQLite query for a quick sample of the dataset.

If you publish articles based on this dataset, please cite the following paper:

J. McAuley and J. Leskovec. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013.
