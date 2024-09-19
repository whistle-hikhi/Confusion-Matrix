# Confusion-Matrix

A Confusion Matrix is a performance measurement tool used for classification problems. It is a table layout that allows visualization of the performance of an algorithm, especially for supervised learning models. The matrix compares the actual target values with those predicted by the machine learning model.

| | Actual Positive | Actual Negative |
| --- | --- | --- |
| Predicted Positive | TP | FP |
| Predicted Negative | FN | TN |

A confusion matrix has four components for binary classification:

- True Positives (TP): The number of positive cases that were correctly predicted as positive.
- True Negatives (TN): The number of negative cases that were correctly predicted as negative.
- False Positives (FP): The number of negative cases that were incorrectly predicted as positive (also known as Type I error).
- False Negatives (FN): The number of positive cases that were incorrectly predicted as negative (also known as Type II error).

## Metrics Derived from Confusion Matrix:
- Accuracy = (TP + TN) / (TP + TN + FP + FN)
- Precision = TP / (TP + FP)
- Recall (Sensitivity) = TP / (TP + FN)
- F1 Score = 2 * (Precision * Recall) / (Precision + Recall)
