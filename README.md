**Project is being completed in multiple steps.**

Step 1:

Goal: gender classification based on a name.

Dataset contains 5000 first names.

Approach: 
Naive Bayes on the last, last two and first character in each name.
SVM applied on the dataset with tfidf vectorization.
Multilayer perceptron on the dataset with tfidf vectorization.
Recurrent neural network with LSTM layers, dropout layers and dense layers.

Step 2: 

Goal: sentiment classification based on IMDB dataset. 

Dataset: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Approach: 
Clean, preprocess (tokenize, stem and remove stop words), find uniques tokens and convert into integers.
Apply a recurrent neural network with a bidirectional LSTM layer. 

