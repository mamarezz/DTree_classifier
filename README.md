# Decision Tree Classifier on Iris Dataset
This project implements a Decision Tree classifier from scratch in Python. The classifier is trained and tested on the well-known Iris dataset, which contains features of iris flowers and their corresponding species labels.

Overview

The code in this repository includes:

Data Loading: Loading the Iris dataset using sklearn.datasets.

Data Preprocessing: Splitting the dataset into training and testing sets.

Decision Tree Implementation: A custom implementation of a Decision Tree classifier, including methods for finding the best split, calculating information gain, and predicting labels.

Model Training: Training the Decision Tree model on the training data.

Model Evaluation: Evaluating the model's performance on the test data using accuracy as the metric.
# Dataset
The Iris dataset consists of 150 samples from each of three species of Iris flowers (Iris setosa, Iris virginica, and Iris versicolor). Four features are measured for each sample: the lengths and the widths of the sepals and petals.

# Code Structure
Node Class: Represents a node in the decision tree, which can either be a leaf node with a prediction value or an internal node with a feature and threshold for splitting.

DecisionTree Class: Implements the Decision Tree algorithm with methods for fitting the model to the data and making predictions.
