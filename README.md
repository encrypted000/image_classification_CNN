# Image Classification

In this project I used Street View House Number (SVHN) dataset. link: http://ufldl.stanford.edu/housenumbers/
SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. It can be seen as similar in flavor to MNIST (e.g., the images are of small cropped digits), but incorporates an order of magnitude more labeled data (over 600,000 digit images) and comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.

# Overview

10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
73257 digits for training, 26032 digits for testing, and 531131 additional, somewhat less difficult samples, to use as extra training data
Comes in two formats:
  1. Original images with character level bounding boxes.
  2. MNIST-like 32-by-32 images centered around a single character (many of the images do contain some distractors at the sides).

# Project Overview

**Aims**
The aim of this project is to develop a Neural network using three different technologies CNN FFNN Logistic regression.

**Objective**
Preprocessing the dataset including techniques like resizing, and normalization.
Deploying neural network model for CNN and using techniques like (Convolutional layers, max pooling layer, Activation layers, fully connected layers), FFNN(input layer, hidden layer, output layer), Logistic Regression(input layer, output layer)
Evaluating model efficiency for SVHN dataset and five feedback of why certain model performs better than other models.
To analyze errors that occurred in the model by interpreting the result
