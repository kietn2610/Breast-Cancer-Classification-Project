# Breast-Cancer-Classification-Project

This project aims to compare different machine learning methods—like decision trees, bagging, AdaBoost, and random forests—on a breast cancer dataset. We want to see which method gives the most accurate predictions for identifying whether a breast tumor is benign or malignant. By varying parameters like the number of estimators or features considered, we can understand how these methods perform and which settings work best for this specific task. Ultimately, this helps us choose the most effective approach for this classification problem.

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
![image](https://github.com/kietn2610/Breast-Cancer-Classification-Project/assets/80939100/e0939383-d2c9-4be0-9fe2-dc6f9238dc15)


Bagging: The plot shows how the accuracy improves with increasing n_estimators (number of base models) in bagging. More estimators generally lead to better performance until a certain point.

AdaBoost: The plot demonstrates how accuracy increases with more n_estimators (weak learners) in AdaBoost. AdaBoost focuses on improving performance by iteratively correcting errors made by previous models.

Random Forest: The plot illustrates how changing max_features (number of features considered at each split) affects accuracy in Random Forest. Different settings of max_features influence the trade-off between bias and variance, impacting model performance.



