# Breast-Cancer-Classification-Project

This project involves using various ensemble methods and decision trees to classify breast cancer data using scikit-learn. We'll be evaluating the performance of decision trees, bagging, AdaBoost, and random forests for this classification task.

Steps:
1) Load Data: Load the Breast Cancer dataset from scikit-learn.
2) Data Splitting: Split the dataset into training and testing sets.
3) Implement different classifiers:
Decision Tree,
 Bagging,
 AdaBoost,
 Random Forest.
 Evaluate each classifier's accuracy and visualize the results.

![image](https://github.com/kietn2610/Breast-Cancer-Classification-Project/assets/80939100/b3bc3a1f-2ac8-405b-aa37-0105b628550f)
![image](https://github.com/kietn2610/Breast-Cancer-Classification-Project/assets/80939100/5c9a54e1-41a3-4428-9029-60bad4fa8f4c)
![image](https://github.com/kietn2610/Breast-Cancer-Classification-Project/assets/80939100/6f97607c-e35c-4619-9320-9031b305abe1)

Bagging: The plot shows how the accuracy improves with increasing n_estimators (number of base models) in bagging. More estimators generally lead to better performance until a certain point.

AdaBoost: The plot demonstrates how accuracy increases with more n_estimators (weak learners) in AdaBoost. AdaBoost focuses on improving performance by iteratively correcting errors made by previous models.

Random Forest: The plot illustrates how changing max_features (number of features considered at each split) affects accuracy in Random Forest. Different settings of max_features influence the trade-off between bias and variance, impacting model performance.

