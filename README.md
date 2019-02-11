CS 7641 Assignment 1: Supervised Learning


The goal of this project is to understand the computational and predictive performance of 5 supervised machine learning algorithm, which includes Decision Tree, Boosting, Support Vector Machine (SVM), K Nearest Neighbors (KNN) and Neural Network. 

Dataset

Each algorithm will be run for two binary classification datasets so that we can compare and contrast them for two different problems.

Dataset_1: Customer Churn Prediction
                  Based on a customer's attributes to predict whether he or she will churn.
                  The dataset is taken from Kaggle: https://www.kaggle.com/blastchar/telco-customer-churn/downloads/telco-customer-churn.zip/1
Dataset_2: Client Subscribe Prediction 
                 Based on the customer's attributes to predict whether he or she will make purchase on black Friday.
                 This dataset is taken from UCI : https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

Getting Started & Prerequisites

For testing on your own machine, you need only to install python 3.7 and the following packages:

	pandas, numpy, pandas, seaborn, IPython, scikit-learn, matplotlib, pydotplus

Running the Classifiers

Work with the iPython notebook (.ipnyb) using Jupyter or a similar environment. This allows you to "Run All" or you can run only the classifiers that you are interested in.


Three Major Parts: 
Data Load & Preprocessing : This section loads the data, performs one-hot encoding, scales numeric features, and split train/test dataset.

Machine Learning: deep dive on each supervised learning model

Model Comparison Plots : learning rate for different models.
