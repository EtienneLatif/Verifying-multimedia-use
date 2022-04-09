# Verifying-multimedia-use

A solution to the MediaEval 2015 Verifying Multimedia Use task. 

## Task

Train machine learning algorithms to classify tweets as real of fake. Algorithms are to be trained on a set of 14,277 instances and tested on a set of 3,755 instances. My implementation is written in Python.

## Preprocessing

-Changing data labelled 'humor' to 'fake' <br/>
-Removing unwanted content such as URLs and emojis<br/>
-Removing stop words<br/>
-Tokenising and lemmatising the words<br/>
-Creating two pairs of training and testing sets with bag-of-words and TF-IDF vectorisation<br/>

## Algorithms

-Multinomial Naive-Bayes<br/>
-Passive-Aggressive<br/>
-Support vector machine<br/>

## Evaluation

-All algorithms had better F1 scores with TF-IDF vectorisation<br/>
-Best F1 score obtained by multinomial Naive-Bayes with TF-IDF: 0.895
