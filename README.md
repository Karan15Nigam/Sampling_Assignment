# Sampling
**Credit Card Fraud Detection – Sampling Techniques Study
Overview**

In real-world datasets, one class often appears much more frequently than the other. This project explores how different sampling techniques affect the performance of various machine learning models when working with a highly imbalanced credit card fraud dataset.

The goal of this work is not just to build a model, but to understand how data balancing methods influence model accuracy and why choosing the right sampling technique matters.

**Dataset**

The dataset used contains credit card transaction records where:

Most transactions are legitimate

Only a very small number are fraudulent

Because fraud cases are rare, the dataset is highly imbalanced. This makes it a good example for studying sampling techniques used in machine learning.

**What Was Done
**
The project was completed in the following steps:

1)Explored the dataset to understand the class imbalance.

2)Created five samples using Stratified 5-Fold Cross Validation so that each split preserved the original class distribution.

3)Applied five different sampling techniques to handle the imbalance:

-No sampling (original dataset)

-Random Oversampling

-SMOTE

-Random Undersampling

-SMOTE with Tomek Links (hybrid method)

4)Trained five different machine learning models on each sampling method:

-Logistic Regression

-Decision Tree

-Random Forest

-K-Nearest Neighbors

-XGBoost

5)Evaluated model performance using accuracy, averaged across all five folds.

6)Compared results and analyzed which sampling technique worked best for each model.
