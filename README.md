# EMG-Signal-Analysis-Using-Deep-Learning

## Dataset

https://archive.ics.uci.edu/ml/datasets/sEMG%20for%20Basic%20Hand%20movements

## Abstract

The main goal of the project is to examine the numerous aspects and characteristics of the EMG signal using various classifiers and derive significant statistical data from it. It can often be challenging to identify specific hand motions or even anomalies because they are frequently subtle or challenging to assess. For movement classification, different machine learning techniques are employed like SVM, LR, Neural Network, Naive Bayes, K-means and GMM. In this work, there are six criteria for classifying motion. EMG data from five different people with six hand signals were used in the project. The classification results were compared in terms of training time parameters and classification accuracy.

## Proposed Methodology

Our categorization model construction process will consist of the following five high level steps:
1. Smoothing and removing noise from data points during preprocessing.
2. Dimensionality reduction using ISOMAP and principal component analysis.
3. Scale the data using conventional methods.
4. Constructing different model classifiers using SVMs, k-means, and gaussian mixture, Neural networks, logistic regression, and naive bayes.
5. Using grid search and cross-validation to hypertune each model and choose the best one.
6. Examine model performance in comparison to a test set and contrast outcomes.

## Outcome

![image](https://github.com/rittikadeb/EMG-Signal-Analysis-Using-Deep-Learning/assets/76259897/058c6230-7425-4992-9984-6f34349bada6)

The acquired classification results were compared to the parameters for classification accuracy and standard deviation. The Gaussian Mixture Trees model, with an average classification accuracy of 77.77% among these models, has been found to have the highest classification performance according to the test findings.
