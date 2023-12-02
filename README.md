# Shahnawaz_covid_19_tweet_sentiment_analysis
Introduction This project uses machine learning to analyze sentiment in tweets related to COVID-19. The goal is to understand how people are feeling about the pandemic and its impact on their lives.

Data The data for this project consists of tweets related to COVID-19 collected from the Twitter API. The tweets are pre-processed to remove any irrelevant information and cleaned to prepare for sentiment analysis.

Methodology The sentiment analysis is performed using a supervised machine learning model. The model is trained on a dataset of labeled tweets and is then used to predict the sentiment of new, unlabeled tweets.

Requirements Python 3.x scikit-learn pandas tweepy nltk Usage Run pip install -r requirements.txt to install necessary packages. Get your Twitter API keys and access tokens and put them in config.py Run python collect_data.py to collect tweets from twitter. Run python preprocess_data.py to preprocess the collected tweets. Run python train_model.py to train the sentiment analysis model. Run python predict_sentiment.py to predict the sentiment of new tweets. Contribution We welcome contributions to this project. If you're interested in contributing, please fork the repository and make your changes. Then submit a pull request for review.
