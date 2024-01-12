# Movie-Review-Sentiment-analysis
Using Text CNN

The IMDB dataset of movie reviews and corresponding sentiment is taken from Kaggle: https://www.kaggle.com/code/shubhamptrivedi/sentiment-analysis-on-imdb-movie-reviews/input. After basic data cleaning it is preprocessed by various NLP techniques such as removing special characters, removing stopwords, and stemming. After tokenization and padding,  by adding a neural network layer for word embedding text CNN model was built. Running ten epochs gave a test accuracy of 87.4. Meanwhile when the model was built using RNN the test accuracy was less i.e, 0.603. Later the model is used to predict the sentiment of test data.
