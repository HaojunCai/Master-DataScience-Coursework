# Data Processing & Modeling Coursework during my Master's

Author: Haojun Cai (haojuncai1996@gmail.com)

## Introduction
This repo includes coursework related to data preprocessing, modeling (regression, classification, clustering, and neural network), and parameters/results analysis from courses including image interpretation, introduction to machine learning, advanced machine learning during my Master's at ETH Zurich.

## File Structure
  - 01_FeatureExtraction.ipynb: implemented Gaussian smoothing and then edge detection on images, calculated variances and plotted image pixel values
  - 02_Regression.ipynb: reconstructed the right part of human face from the left part of a human face using two regression models: 1) polynomial fitting whose optimal degree was found by spotting the elbow point of MSE resp. degree, 2) ridge regression with regularization and cross-validation to find the optimal hyperparameters
  - 03_Classification.ipynb: applied nearest neighbour classification (KNN), linear discriminant analysis, logistic regression, and decision tree algorithms into land use classification (buildings, vegetation); applied logistic regression and decision tree on breast cancer classification (benign and malignant tumor); compared results between different models
  - 04_CNN_Classification.ipynb: developed convolutional neural network to tackle competition on dog VS cat classification
  - 05_UnsupervisedClustering.ipynb: implemented K-means and mean shift unsupervised clustering algorithms from scratch (without using scikit-learn package)
