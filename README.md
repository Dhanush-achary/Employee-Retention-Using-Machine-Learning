# Predicting Employee Retention Using Machine Learning Models

## Project Summary

This project aims to develop a machine learning solution to predict employee churn using three different models: Gradient Boosting Classifier, XGBoost Classifier, and Random Forest.

### Objective
To build and evaluate machine learning models for predicting employee retention and providing actionable insights to improve retention strategies.

### Key Results
- **Random Forest**: Achieved the highest accuracy of 81%, outperforming the other models. It exhibited balanced precision and recall metrics:
  - **Class 0**: Precision - 0.78, Recall - 0.61
  - **Class 1**: Precision - 0.83, Recall - 0.91
- **XGBoost Classifier**: Attained an accuracy of 79%, with solid performance in classification:
  - **Class 0**: Precision - 0.72, Recall - 0.59
  - **Class 1**: Precision - 0.81, Recall - 0.89
- **Gradient Boosting Classifier**: Reached an accuracy of 78%. While performing decently, improvements are needed in classifying class 0 instances.

### Actionable Insights & Recommendations
1. **Grade & Joining Designation**: High correlation (0.71) indicates that career progression paths and training programs can be leveraged to improve retention.
2. **Income & Grade**: A correlation of 0.74 suggests that revising the compensation structure in line with employee performance and tenure is essential.
3. **Quarterly Rating**: Employees with improving quarterly ratings are less likely to churn. Implementing strategies for regular feedback and recognition is recommended.
4. **Monthly Salary Increase**: A lack of salary increase correlates with higher churn. Regular salary reviews can help retain top talent.
5. **Machine Learning Model Insights**: Random Forest's superior performance indicates its potential for proactive churn management. Further optimization and integration with HR systems are recommended.
