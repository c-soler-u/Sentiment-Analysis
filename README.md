# Sentiment-Analysis
Sentiment analysis of the IMBD data-set of 50.000 reviews annotated as positive or negative. The data-set can be found at https://ai.stanford.edu/~amaas/data/sentiment/ . We preoprocess the data using Spacy and remove non function words and stopwords and apply lemmatization. Then, using the tf-idf vectorizer, we convert each review into a Numpy array and use it for training. The Naive Bayes algorithm is used in this case achieving a model with a 86% accuracy over test.  

