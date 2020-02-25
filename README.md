# Quora questions' similarity.

***quora_questions_similarity/***

Objective: identify duplicate questions in the Quora Question Pairs dataset. Make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers. 

Dataset: https://www.kaggle.com/c/quora-question-pairs

Approach: 
GloVe for word embeddings, Siamese Neural Network using Keras.

# Gender classification based on a first name.

***gender_classification/***

Objective: classify a first name either as male or female.

Dataset contains 5000 first names.

Approach: 
Naive Bayes on the last, last two and first character in each name.
SVM applied on the dataset with tfidf vectorization.
Multilayer perceptron on the dataset with tfidf vectorization.
Recurrent neural network with LSTM layers, dropout layers and dense layers.


