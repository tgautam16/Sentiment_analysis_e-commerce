# Sentiment_analysis_e-commerce

This code does sentiment analysis of Women's clothes reviews. The data-set is labelled in two classes: "Recommended: 1" and "Not Recommended: 0".

After cleaning and analysing each column of the dataset closely, I create wordclouds of both positive and negative sentiments in the reviews. 

To do a predictive analysis and train ML models, I perform Tokenization, Noise-Removal, and Lemmatization of each review. I then remove rare words from the reviews.

The data is then split into test and training data.

The training data is converted in two sets of vectors: Count Vectorizer and TF-IDF Vectorizer.

Each of these sets of training data are then used to train four ML classification models: Logistical Regression, Multinomial Naive Bayes, Support Vector Machine (SVM), and Random Forest. 

K-Fold cross validation is performed on each model (with different metrics).

F1 Score, Recall, and Average precision scores are used to determine the best perfoming model, which turned out to be Logistic Regression for Average Precision.

[Find full notebook here.](https://nbviewer.org/github/tgautam16/Sentiment_analysis_e-commerce/blob/main/Customer_reviews_sentiment_analysis_size_red.ipynb)

