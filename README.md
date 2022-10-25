# ConfussionMatrixClassifier

The code aims to elaborate a summary of prediction results on a classification problem by determining the number of TP, FP, FN and TN:

- TP (True Positives): Point is both expected and found
- FN (False Negatives): Point is expected but not found
- FP (False Positives): Point is not in expected but is found
- TN (True Negatives): Point is neither expected nor found (usually undefined)

The number of TP, FP, FN and TN is obtained by comparing the set of expected points and the set of found points.

Aspects to consider when trying to classify into TP, FN, FP

1 - Each expected value corresponds to more than one prediction (Only choose one as a True Positive, the rest must be classified as False Positives)

2 - No predictions found for an expected value

3 - Expected values difference is smaller than the threshold

4 - Found values are within two expected values' threshold

5 - Null values, structural errors (If there are any)
