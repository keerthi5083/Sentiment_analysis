# Sentiment_analysis
Using Logistic Regression and Naive Bayes

This project performs sentiment analysis on IMDb movie reviews using Natural Language Processing (NLP) and machine learning. The raw reviews are preprocessed by removing HTML tags, special characters, stopwords, and applying stemming to normalize the text. The dataset is split into 30,000 training and 20,000 testing reviews. Text is converted into numerical features using CountVectorizer (Bag of Words) with unigrams and bigrams, removing rare and overly common words. Machine learning models such as Logistic Regression and Naive Bayes are trained on these vectors to classify reviews as positive or negative, demonstrating how NLP pipelines convert raw text into actionable features for sentiment classification.
