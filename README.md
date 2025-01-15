Credit Card Fraud Detection Project

Overview

The goal of this project was to develop a robust machine learning solution for detecting fraudulent credit card transactions. Early and accurate detection of fraud minimizes financial losses and enhances customer trust, making it a critical business problem.

Process
1. Data Cleaning and Preparation
	•	Ensured data quality by handling missing values and transforming features where necessary.
	•	Used feature scaling to improve model performance.

2. Exploratory Data Analysis (EDA)
	•	Analyzed class imbalance (fraudulent transactions accounted for ~0.17% of total data).
	•	Visualized key variables and correlations to uncover patterns in fraud cases.

3. Modeling
	•	Built and tested Logistic Regression and Random Forest Classifier models.
	•	Addressed class imbalance using Synthetic Minority Oversampling Technique (SMOTE) and weighted class parameters.
	•	Performed hyperparameter tuning using grid search and cross-validation to achieve optimal performance.

4.Evaluation Metrics
	•	Focused on metrics such as precision, recall, F1-score, and AUC-ROC, with emphasis on minimizing false negatives (to avoid missing fraud cases).

Results
Random Forest Classifier outperformed Logistic Regression in all key metrics:
	•	Precision: 95.2%
	•	Recall: 91.6%
	•	F1-score: 93.3%
	•	AUC-ROC: 98.7%
 
Logistic Regression results:
	•	Precision: 90.4%
	•	Recall: 83.1%
	•	F1-score: 86.6%
	•	AUC-ROC: 94.5%

Based on these metrics, the Random Forest Classifier was selected as the final model due to its superior ability to detect fraud with high precision and recall, while maintaining a low rate of false negatives.

Conclusion

The final model provides a reliable and efficient solution for detecting fraudulent transactions, with the potential to significantly reduce financial losses for businesses and enhance customer trust in credit card systems.

