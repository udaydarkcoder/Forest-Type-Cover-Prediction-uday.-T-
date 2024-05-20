# Forest-Type-Cover-Prediction-uday.-T-
It's my fourth capstone project

 # Forest Type Cover Prediction Project

## Project Overview

The Forest Type Cover Prediction project focuses on accurately predicting seven distinct cover types within four different wilderness areas using machine learning models. The goal is to determine the optimal approach for real-world deployment based on the analysis of model performance and comparison.

## Dataset Summary

The dataset contains 55 columns and 15,120 rows, devoid of any missing values. The target variable, "Cover_Type," is evenly distributed among 7 classes, each representing approximately 14.29% of the total observations.

## Model Performance Overview

1. **Extra Trees Classifier:**
   - Accuracy: 86%
   - F1 Score: 86%
   - Cross-Validation Score: 78.06%
   - Best Parameters: {'n_estimators': 150}
   - Performance Significance: No statistically significant difference was observed.

2. **Random Forest Classifier:**
   - Accuracy: 87.24%
   - F1 Score: 87.04%
   - Cross-Validation Score: 78.31%
   - Best Parameters: {'n_estimators': 150}
   - Performance Significance: Significantly better than the benchmark.

3. **AdaBoost Classifier:**
   - Accuracy: 40%
   - F1 Score: 30%
   - Cross-Validation Score: 39.36%
   - Best Parameters: {'n_estimators': 150}
   - Performance Significance: No significant deviation detected.

4. **Gradient Boosting Classifier:**
   - Accuracy: 80%
   - F1 Score: 80%
   - Cross-Validation Score: 72.33%
   - Best Parameters: {'n_estimators': 150}
   - Performance Significance: No clear distinction in performance.

5. **K-Nearest Neighbors:**
   - Accuracy: 78%
   - F1 Score: 78%
   - Cross-Validation Score: 69.21%
   - Best Parameters: {'n_neighbors': 3}
   - Performance Significance: No observable variation.

6. **Stochastic Gradient Descent Classifier:**
   - Accuracy: 66%
   - F1 Score: 64%
   - Cross-Validation Score: 58.80%
   - Best Parameters: {'alpha': 0.0001, 'loss': 'hinge'}
   - Performance Significance: No statistically significant difference.

7. **Logistic Regression:**
   - Accuracy: 68%
   - F1 Score: 68%
   - Cross-Validation Score: 62.94%
   - Best Parameters: {'C': 10}
   - Performance Significance: No notable deviation in performance.

## Best Model Selection

The **Random Forest Classifier** emerged as the optimal selection for production tasks due to its exceptional performance metrics and robustness demonstrated across evaluation criteria. This model stood out with the highest accuracy of 87.24% and maintained a superior cross-validation score of 78.31%.

## Conclusion

The **Random Forest Classifier** proved to be the prime candidate for accurately predicting forest cover types within designated wilderness areas, showcasing a remarkable accuracy of 87.24% and robust performance across various evaluation metrics. This model surpassed the other algorithms in terms of overall accuracy and consistency, making it the preferred choice for real-world deployment in the Forest Type Cover Prediction project.

## My Contribution

My contributions to this project include the initial data exploration, feature selection, and modelling to establish the effectiveness of the Random Forest Classifier. I also participated in the rigorous evaluation of each model's performance to ensure the selection of the most suitable model for real-world deployment. Furthermore, I actively engaged in the comprehensive analysis of the dataset and model results to provide valuable insights for the project's success.
