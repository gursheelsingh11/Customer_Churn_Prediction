# Customer_Churn_Prediction
Conducted a comparative evaluation of multiple machine learning models to predict customer churn, including Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, Decision Tree, and Random Forest classifiers. Model performance was assessed using accuracy, precision, recall, F1-score, and confusion matrix metrics to account for class imbalance and business relevance.
<br>
The Logistic Regression model achieved the highest overall accuracy of 80.3%, indicating strong generalization and interpretability. However, it demonstrated moderate recall (54.5%), meaning a significant portion of churn customers were not identified.
<br>
The Random Forest model provided the best balance between precision and recall, achieving the highest F1-score of 0.63 and a recall of 78.3%, making it the most effective model for identifying potential churn customers while maintaining acceptable false positives.
<br>
The Naive Bayes model achieved high recall (85.3%) but suffered from low precision (43.3%), leading to a large number of false positives, which may result in inefficient retention strategies. The KNN and Decision Tree models showed comparatively lower predictive performance, with reduced F1-scores and recall values.
<br>
Overall, Random Forest was selected as the preferred model for churn prediction due to its strong predictive stability and ability to capture churn behavior, while Logistic Regression served as a reliable baseline model. This analysis highlights the importance of evaluating models beyond accuracy when working with imbalanced datasets such as customer churn.

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|------------|-------------|----------|------------|
| Logistic Regression | **80.3%** | 0.65 | 0.55 | 0.59 |
| KNN | 74.4% | 0.52 | 0.47 | 0.49 |
| Naive Bayes | 66.5% | 0.43 | 0.85 | 0.57 |
| Decision Tree | 78.1% | 0.61 | 0.50 | 0.55 |
| Random Forest | 76.1% | 0.53 | **0.78** | **0.63** |
