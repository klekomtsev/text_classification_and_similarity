# Identification of duplicate questions using twin neural networks.

***quora_questions_similarity/***

Objective: identify duplicate questions in the Quora Question Pairs dataset. Make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers. 

Dataset: https://www.kaggle.com/c/quora-question-pairs

Performance:

- Best test AUC = 0.88, Precision (duplicate) = 0.75.

Methods: 

- One-shot learning using twin neural networks with time distributed and LSTM layers. 

- Pre-trained GloVe embeddings. 

- Jaccard, Manhattan, cosine similarity metrics.

Dataset info:

Total number of questions pairs: 404,278

Portion of not duplicate reviews: 0.63

Portion of duplicate reviews: 0.37

