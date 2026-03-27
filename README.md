# Saiket-Systems-Internship-Task-4-Churn-Prediction-Model-
# Logistic Regression Performance
- Accuracy: 80.2%
- Precision: 79.6%
- Recall: 80.2%
- F1-score: 79.8%
# Decision Tree Performance
- Accuracy: 72%
- Precision: 47%
- Recall: 51%

# Top drivers:
- MonthlyCharges
- Contract
- TotalCharges
- Tenure
# Model Comparison
Metric	Logistic Regression	Decision Tree
- Accuracy	80%	72%
- Precision	High	Low
- Recall	High	Moderate

The results show that the Logistic Regression model performs significantly better than the Decision Tree model in predicting customer churn, achieving about 80% accuracy with well-balanced precision, recall, and F1-score. This indicates that the model is reliable in correctly identifying both churners and non-churners, with a strong ability to detect actual churn cases while minimizing false predictions. In contrast, the Decision Tree model shows lower overall performance with about 72% accuracy and relatively weak precision and recall, meaning it struggles more with correctly identifying churners and produces more incorrect predictions. However, the Decision Tree provides valuable insights into the key drivers of churn, revealing that factors such as Monthly Charges, Contract type, Total Charges, and Tenure have the strongest influence on whether a customer leaves. These findings reinforce earlier analysis that pricing, customer commitment, and duration of service are critical determinants of churn. Although hyperparameter tuning improved the Decision Tree by reducing overfitting, it still did not match the predictive strength of Logistic Regression. Overall, the results suggest that Logistic Regression is the more suitable model for accurate churn prediction, while the Decision Tree is better used as a complementary tool for interpreting customer behavior and identifying the most important factors influencing churn.
