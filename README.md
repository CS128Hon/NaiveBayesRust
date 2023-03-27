# NaiveBayesRust

# Group Name: H2OandO2

Member names:

Hanshul Bahl    Net ID: hbahl2 

Arshiya Gupta   Netid: arshiya5 

Sharayu Janga  	Net id: sjanga2	



# Project Introduction:

We aim to implement the Naive Bayes Machine Learning Classifier with our understanding of the rust programming language. The Naive Bayes Classifier is based on applying the Bayes Theorem with the assumption that the question of a data point being present in a data set is independent from the data already in the set. To implement Naive Bayes algorithm in Rust programming language, we first need to define our dataset and the problem we are trying to solve. For this example, we will use a dataset of emails labeled as either spam or non-spam, and we will build a classifier that can predict whether a given email is spam or not. We will be tokenizing our input and running it through the classifier. Our algorithm will employ Laplace Smoothing to assign probabilities to non-spam emails. 


# Technical Overview:
We will create a struct to represent the Naive Bayes classifier. The struct will contain a set of classes and two HashMaps. 
Next, we will implement a constructor for the NaiveBayes struct. The constructor should initialize the three fields to empty HashMaps and an empty set.
Then, we will divide the dataset into a training and a test set and train the classifier on the training set by calling it on each entry.
The performance will be evaluated by calling the classifier on the test set using the predict method.


# Challenges:
We might face difficulties working with HashMaps. The process of training our model on a dataset in rust is new to us and we will have to look at other resources to gain knowledge and a better understanding of the process. Naive Bayes algorithms rely heavily on computing probabilities, which can be computationally expensive for large datasets. Rust is known for its performance, but it can still be challenging to optimize code to run efficiently, especially when working with complex data structures.


Checkpoint 1:
Build a basic tokenized model of our classifier so that it is ready to be trained on the Spambase Dataset.

Checkpoint 2:
Train the model on our dataset and work towards the prediction and honing methods.


References:
https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/ 
https://towardsdatascience.com/implementing-naive-bayes-algorithm-from-scratch-python-c6880cfc9c41
