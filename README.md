# MNIST Classification with Feature Engineering

## Overview

This project aims to classify the MNIST dataset, which consists of handwritten digits. The project includes various steps like data loading, preprocessing, feature extraction, and classification using a custom SVM model.

## Data Preprocessing

The MNIST data is loaded and preprocessed to fit the model requirements. This includes:

- Deskewing images to correct the image orientation.
- Applying MinMax and Standard Scalers for normalization.
- Extracting polynomial and convolutional features for enhanced performance.

## Feature Extraction Techniques

1. **Deskewing**: Correcting the alignment of handwritten digits.
2. **Polynomial Feature Extraction**: Enhancing features by generating polynomial combinations.
3. **Convolution Feature Extraction**: Using convolutional operations to extract spatial features.

## Custom SVM Classifier

A custom SVM classifier is implemented with mini-batch stochastic gradient descent for classification. It's tested with different feature sets for optimal performance.

## Principal Component Analysis (PCA)

PCA is applied to reduce the dimensionality of the feature space while preserving the variance as much as possible.
