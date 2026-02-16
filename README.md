My  git project:Credit Card Fraud Detection
Overview
This project implements a machine learning pipeline to identify fraudulent credit card transactions. The primary challenge addressed in this work is the severe class imbalance—where fraudulent transactions represent only a tiny fraction of the total dataset


Technical Stack:
Language: Python

Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

Techniques: Synthetic Minority Over-sampling Technique (SMOTE), Random Forests, Logistic Regression
Key Features

Handling Imbalance: Implemented SMOTE to balance the training set, ensuring the model doesn't just "guess" the majority class.


Feature Engineering: Analyzed transaction time and amount distributions to detect anomalies.


Evaluation Metrics: Focused on Precision-Recall curves and F1-Score rather than simple accuracy, as accuracy is misleading in imbalanced datasets.

Results:
Achieved high recall for fraud detection, ensuring fewer fraudulent transactions go unnoticed.

Successfully handled a dataset where less than 0.2% of transactions were fraudulent.
