# machine-learning-credit-card-fraud-detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset contains 129,000 transactions, of which only 0.5% are fraudulent, presenting a significant class imbalance challenge. The project leverages advanced classification algorithms to achieve high accuracy while addressing real-world business constraints like operational costs and customer satisfaction.

## Features
### Dataset:

129,000 credit card transactions spanning January 2019 to December 2020.
Includes features like transaction amount, age, timestamps, transaction categories, and geolocation data.
Target variable: is_fraud (1 = Fraud, 0 = Legitimate).

## Feature Engineering:

Extracted key predictors such as transaction hour categories, fraud-prone transaction types, and customer behavior patterns.
Addressed class imbalance with targeted feature transformations.
Machine Learning Models:

Gradient Boosting: Achieved high recall (90%) and AUC (0.98), effective for minimizing false negatives.
Random Forest: Balanced recall and precision, achieving an AUC of 0.996 with optimized thresholds for cost-effectiveness.
Evaluation Metrics:

ROC AUC, accuracy, precision, recall, and log loss to ensure robust model comparison.
Cost analysis based on real-world factors like false positive and false negative costs.

## Results
Gradient Boosting: High recall and AUC, suitable for scenarios prioritizing fraud detection over false positives.
Random Forest: Lower false positives and overall cost, making it the more cost-effective solution for deployment.
Optimized thresholds using Youden’s J statistic for business alignment.

## Future Scope
Enhance feature engineering with geolocation-based predictors and transaction frequency analysis.
Explore undersampling or SMOTE techniques to further balance the dataset.
Perform a detailed cost analysis under varying thresholds to fine-tune model performance
