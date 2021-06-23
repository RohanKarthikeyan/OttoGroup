# Otto Group Product Classification Challenge

**Aim:** Distinguish between product categories for effective classification.

## ☑️ What did I do?
  - First, I found that there was a class-imbalance problem and that the features were highly skewed.
    - To tackle the class-imbalance problem, I ensured that the ratio of class labels in the variable specified is constant by using the `stratify` argument in `train_test_split`.
    - To tackle the skew problem, I used `QuantileTransformer`.
  - I then trained various (7, to be precise) classifier models, ranging from KNN to SVMs to CatBoostClassifier, achieving a multi-class loss below 0.5.
