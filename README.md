# machine-learning-text-law-portuguese
This repository contains the code from "A comparison of classification methods applied to legal text data", published in EPIA 2021.

Prepocessing.ipynb is the code for treating the text removing stopwords, wrong words and names. For this is used TF-IDF, NLTK stopwords, commom names in Brazil and regular expression. 
data_clear.csv is the dataset after passing for the preprocessing code, due the privacy of the court the raw data is not avaliable.
Processing.ipynb is the code for training and evaluation of the models of machine learning. The models used Random Forest, Adaboost with decision tree, Naive Bayes, K Nearest Neighbors, Support Vector Machine and Multi Layer Perceptron.
