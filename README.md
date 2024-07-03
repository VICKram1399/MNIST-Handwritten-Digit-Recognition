# MNIST-Handwritten-Digit-Recognition
Built a Machine Learning model that recognizes handwritten digits (0-9) from images.

This project demonstrates the implementation of a machine learning model to accurately recognize handwritten digits (0-9) from images. It utilizes the famous MNIST dataset and a Multi-Layer Perceptron (MLP) classifier.

##Project Overview
Problem: Recognizing handwritten digits is a fundamental task in image classification and has applications in various fields, including optical character recognition (OCR) and automated data entry.

Dataset: The MNIST dataset consists of 70,000 grayscale images of handwritten digits, each 28x28 pixels. It is a widely used benchmark dataset for machine learning models.

Goal: Build and train an MLP classifier to accurately predict the digit represented in an input image.
Methodology
Data Preparation:

The MNIST dataset is loaded using fetch_openml from the scikit-learn library.
The target labels (digit values) are converted to integers.
The data is split into training (80%) and testing (20%) sets.
The pixel values are standardized using StandardScaler to improve model performance.

##Model Selection and Training:

A Multi-Layer Perceptron (MLP) classifier is chosen as the model. It is a type of artificial neural network well-suited for image classification tasks.
The model is trained on the training data using backpropagation and optimization algorithms.
Model Evaluation:

The trained model is evaluated on the testing data.
Performance metrics are calculated, including:
Classification report: Precision, recall, and F1-score for each digit
Confusion matrix: Visualization of prediction accuracy for each digit
Overall accuracy: 98 Percentage of correctly classified digits
