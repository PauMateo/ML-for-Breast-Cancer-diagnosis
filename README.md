# Machine Learning for Breast Cancer diagnosis
Project for the Machine Learning 1 course in the Data Science and Engineering Degree - UPC

## Description
Breast cancer is the most common cancer among women worldwide, accounting for 25% of all cancer cases and affecting approximately 2.1 million people in 2015. This project explores the application of machine learning techniques to automate the diagnosis of breast cancer, focusing on differentiating malignant from benign tumors. We utilized the [Wisconsin Breast Cancer dataset](httpsarchive.ics.uci.edudataset17breast+cancer+wisconsin+diagnostic) containing 569 tumor cell samples, with 30 extracted features representing various morphological aspects.

Following data preprocessing, feature selection was performed to optimize model performance. We trained multiple models, including LDA, QDA, k-NN, Naive Bayes, Decision Tree, Random Forest, Logistic Regression, AdaBoost, and XGBoost. The best models were selected based on cross-validation metrics, prioritizing recall to minimize false negatives. Logistic Regression, AdaBoost, and QDA emerged as the top models, achieving over 95% accuracy and recall on the test set.
