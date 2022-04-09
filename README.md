# Verifying-multimedia-use

A solution to the MediaEval 2015 Verifying Multimedia Use task. 

## Task

Train machine learning algorithms to classify tweets as real of fake. Algorithms are to be trained on a set of 14,277 instances and tested on a set of 3,755 instances. My implementation is written in Python.

## Preprocessing

-Changing data labelled 'humor' to 'fake'
-Removing unwanted content such as URLs and emojis
-Removing stop words
-Tokenising and lemmatising the words
-Creating two pairs of training and testing sets with bag-of-words and TF-IDF vectorisation

## Algorithms

-Multinomial Naive-Bayes
-Passive-Aggressive
-Support vector machine

## Evaluation

-All algorithms had better F1 scores with TF-IDF vectorisation
-Best F1 score obtained by multinomial Naive-Bayes with TF-IDF: 0.895
