Predicting Healthcare Appointment No-Shows Using Statistical and Machine Learning Models

Overview
Missed healthcare appointments ("no-shows") reduce healthcare system efficiency, waste clinical resources, and negatively impact patient care. Predicting which patients are likely to miss appointments enables healthcare providers to implement targeted interventions such as reminder systems and improved scheduling strategies.
This project applies both traditional statistical modeling and modern machine learning techniques to predict patient appointment attendance using real-world healthcare data.
This study evaluates and compares Logistic Regression, Random Forest, and XGBoost models using a dataset of 110,527 patient appointments.


Research Objectives
The primary objectives of this study are:
Evaluate whether statistical models remain competitive with machine learning methods
Identify key predictors influencing patient appointment attendance
Compare predictive performance across statistical and machine learning models
Provide interpretable insights relevant to healthcare operational improvement

Dataset Description
Dataset size: 110,527 patient appointment records
Predictor variables include:
Age
Gender
Scholarship status
Hypertension status
Diabetes status
SMS reminder status
Target variable:
No-show (0 = Attended, 1 = Missed appointment)

Methods
Statistical Method
Logistic Regression was used to evaluate statistical relationships between predictors and appointment attendance.
Statistical hypothesis testing confirmed that age is a statistically significant predictor (p < 0.001).

Machine Learning Models
Two machine learning models were implemented:
Random Forest
Extreme Gradient Boosting (XGBoost)
Models were evaluated using:
Accuracy
Confusion Matrix
ROC Curve
AUC Score
Feature Importance Analysis

Results
Model performance comparison:
Model	Accuracy	AUC Score
Logistic Regression	79.93%	0.603
Random Forest	79.71%	0.601
XGBoost	79.93%	0.613
Key findings:
Machine learning models achieved similar performance to logistic regression
SMS reminders were identified as the most important predictor
Age was the second most important predictor
Statistical models remain highly effective for healthcare predictive modeling

Figures
ROC Curve Comparison
Shows model discrimination ability across Logistic Regression, Random Forest, and XGBoost.
Feature Importance
Identifies SMS reminders as the strongest predictor of appointment attendance.

Research Paper
The full research paper is included in this repository:
Healthcare_NoShow_Research_Paper.pdf
This paper contains:
Statistical analysis
Machine learning modeling
Model evaluation
Feature importance analysis
Healthcare interpretation

Technologies Used
Python libraries:
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

Project Structure
healthcare-no-show-prediction/
│
├── Healthcare_NoShow_Analysis.ipynb
├── Healthcare_NoShow_Research_Paper.pdf
├── figures/
├── README.md
└── requirements.txt

Author
Ayush Nagar
Healthcare Data Analyst
MSc Data Science
BSc Statistics
Research Interests:
Healthcare Analytics, Biostatistics, Machine Learning, Predictive Modeling

Research Significance
This project demonstrates the application of statistical and machine learning techniques in healthcare predictive analytics and highlights the continued relevance of interpretable statistical models alongside modern machine learning approaches.



