# Handwritten Digital Recognition using KNN
## This project demonstrates how to use K-Nearest Neighbours(KNN) algorithm for classifying handwritten digits.

The dataset used is the digits dataset fron scikit-learn.

## KNN works by finding K closest data points to a new sample and assigning the most label among them.

## Dataset
    - Source: sklearn.datasets.load_digits()
    - Number of sample
    - each image: 8x8 grayscale pixels (64 features)
    - labels: digits (0-9)

## Steps
    1. Load digits dataset
    2. split the dataset into train and test
    3. train a KNN classifier with k=5 and others
    4. Evaluate performance using "accuracy score" and classification report"
    5. Visulize predictions

