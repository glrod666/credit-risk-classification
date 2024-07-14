# credit-risk-classification


## Overview

This project involves building a logistic regression model to predict whether a loan is healthy (0) or high-risk (1). The model is evaluated based on its performance metrics such as precision, recall, F1-score, and overall accuracy.

## Dataset

The dataset contains labeled data for loans. Each row represents a loan, and the features include various attributes related to the loan and the borrower. The label indicates whether the loan is healthy (0) or high-risk (1).

## Model

We use a logistic regression model to predict the loan status. Logistic regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome.

## Performance Metrics

The performance of the model is evaluated using the following metrics:

- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-Score**
- **Accuracy**

### Confusion Matrix
```plaintext
array([[18655,   110],
       [   36,   583]], dtype=int64)
```

- **True Negatives (TN)**: 18,655 (correctly predicted healthy loans)
- **False Positives (FP)**: 110 (incorrectly predicted high-risk loans)
- **False Negatives (FN)**: 36 (incorrectly predicted healthy loans)
- **True Positives (TP)**: 583 (correctly predicted high-risk loans)

### Classification Report
```plaintext
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384
```

### Summary

1. **Healthy Loans (Label 0)**
   - **Precision**: 1.00
   - **Recall**: 0.99
   - **F1-Score**: 1.00

2. **High-Risk Loans (Label 1)**
   - **Precision**: 0.84
   - **Recall**: 0.94
   - **F1-Score**: 0.89

3. **Overall Accuracy**: 0.99

### Explanation

- **For Healthy Loans**: The model performs exceptionally well with almost perfect precision, recall, and F1-score.
- **For High-Risk Loans**: The model performs well with good precision and high recall.
- **Overall**: The model is highly reliable with an overall accuracy of 99%.



## Conclusion

The logistic regression model is highly effective in predicting the health status of loans, with almost perfect performance for 
healthy loans and strong performance for high-risk loans. The overall accuracy of 99% demonstrates the mode's  reliability.


## Acknowledgments
Xexpert learning assistant 
previous class examples



