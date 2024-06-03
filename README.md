# Credit card Fraud Detection by various machine learning model ( CLF, Random Forest,..) using SMOTE technique to oversampling data
Overview

This project focuses on developing a machine learning solution for detecting fraudulent transactions using credit card data. Given the financial and personal implications of credit card fraud, it's crucial to have robust and accurate systems in place to detect and prevent such activities. This project explores the efficacy of various machine learning classifiers in distinguishing between fraudulent and non-fraudulent transactions.
Data Description

The dataset used in this project consists of transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred over two days and includes examples of both fraudulent and non-fraudulent transactions. Due to the sensitive nature of financial records, the features are transformed using PCA (Principal Component Analysis), resulting in numerical input variables that are less interpretable but maintain the essential characteristics needed for analysis.
Problem Statement

The dataset is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions. This imbalance makes it challenging for predictive models to detect fraudulent transactions effectively, as they tend to be biased towards the majority class (non-fraudulent transactions).

Objectives

    To implement various machine learning models to identify patterns indicative of fraud.
    To handle the imbalanced dataset effectively using SMOTE (Synthetic Minority Over-sampling Technique) to oversample the minority class, thereby providing the models with a more balanced dataset and improving their ability to classify minority class samples accurately.

Models Used

    Logistic Regression: A baseline model for binary classification tasks, providing a foundation for performance comparison.
    Random Forest Classifier: An ensemble method that uses multiple decision trees to improve classification accuracy and control over-fitting.

Methodology

    Data Preprocessing: Includes scaling of non-PCA features and handling missing values if any.
    Handling Imbalanced Data: Utilizing SMOTE to artificially increase the number of samples in the minority class.
    Model Training and Evaluation: Each model is trained on the resampled dataset and evaluated on a separate test set to gauge its performance. Key metrics include accuracy, precision, recall, F1-score, and the ROC curve.

Challenges Addressed

    Class Imbalance: Enhanced focus on overcoming the challenge of an imbalanced dataset that could bias models towards predicting non-fraudulent transactions.
    Feature Engineering: Limited scope due to PCA-transformed features, with efforts focused more on model tuning and selection.
