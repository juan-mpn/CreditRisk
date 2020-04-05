# Predicting Credit Risk
*Python* and Machine Learning: Using pandas and *Skikit-learn* to predict Credit Risk
ML![alt text](https://www.datacamp.com/courses/data-science-for-business)

## Background
**Supervised Machine Learning** and Predicting Credit Risk, evaluating several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company.

## Objectives
The goals of this challenge are:

- Implement machine learnin models
- Use Credit Risk *Resampling Techniques* to address class imbalance
- Evaluate the performance of machine learning models

**Using `imabalanced-learn` library to resample the data and build and evaluate logistic regression classifiers using the resampled data**

Oversample the data using the RandomOverSampler and *SMOTE* algorithms.
Undersample the data using the cluster centroids algorithm.
Use a combination approach with the *SMOTEENN* algorithm.
For each of the above you will find:

1. Train a logistic regression classifier (from *Scikit-learn*) using the resampled data.
2. Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
3. Generate a confusion_matrix.
4. Print the classification report (`classification_report_imbalanced from imblearn.metrics`).

## Files / Target
`../Resources/LoanStats_2019Q1.csv`

*`target = ["loan_status"]`*
+ Low Risk  68,470
- High Risk    347

Finding that the data from LendingClub it is imbalanced with 68,470 Low Risk applicants vs 347 High Risk we used Resampling Techniques and various Machine Learning models described below. This will help us further fine tune by training our machine learning models with balanced data. 

## Machine Learning Models Analysis
# Credit Risk Resampling using Naive Random Oversampling
+ Low Risk  51,366
- High Risk 51,366

**Balanced Accuracy Score : 0.644711676499736**


