Heart Disease Prediction Using Machine Learning

Project Overview :

This project aims to develop a machine learning model to predict the presence of heart disease in individuals based on various health metrics. By leveraging data analysis and classification models, this project supports SDG 3: Good Health and Well-being, providing a tool that could aid in early diagnosis and preventive healthcare.

Dataset : 

The dataset used for this project is the Heart Disease UCI dataset from the UCI Machine Learning Repository. It includes various features such as:

	•	Age: Age of the patient
	•	Sex: Gender
	•	Chest Pain Type: Type of chest pain experienced
	•	Resting Blood Pressure: Blood pressure at rest
	•	Cholesterol: Serum cholesterol level
	•	Fasting Blood Sugar: Blood sugar level after fasting
	•	Resting ECG: Electrocardiographic results
	•	Max Heart Rate: Maximum heart rate achieved
	•	Exercise-Induced Angina: Angina induced by exercise
	•	ST Depression: Depression induced by exercise relative to rest
	•	Slope of ST Segment
	•	Number of Major Vessels: Number of vessels colored by fluoroscopy
	•	Thalassemia
	•	Target: Indicator of heart disease presence (0 = No disease, 1 = Disease)

Objective : 

The objective of this project is to build a classification model that accurately predicts the likelihood of heart disease based on health metrics. This can help with early diagnosis and enhance preventive care practices.

Workflow : 

	1.Data Preprocessing:
		•Handled missing values by imputing medians.
		•Converted the target variable to binary, representing disease presence (1) or absence (0).
		•Applied SMOTE to address class imbalance.
		•Standardized features for better model performance.
  
	2.Model Training and Validation:
		•Three models were trained: Logistic Regression, Decision Tree, and Random Forest.
		•Evaluated each model using 10-fold cross-validation on metrics such as accuracy, precision, recall, F1-score, and AUC.
  
	3.Model Evaluation:
		•Split data into train and test sets.
		•Evaluated the best-performing model (Random Forest) on the test set and compared metrics.

Models Used : 

	•	Logistic Regression: A linear model that predicts the probability of a binary outcome.
	•	Decision Tree Classifier: A non-linear model that splits data based on feature values to make predictions.
	•	Random Forest Classifier: An ensemble model combining multiple decision trees to improve prediction accuracy and control overfitting.

Results : 

The Random Forest model achieved the highest performance, indicating its suitability for this dataset. Key metrics for Random Forest are as follows:

	•	Accuracy: ~85%
	•	Precision: ~86%
	•	Recall: ~84%
	•	F1 Score: ~85%
	•	AUC Score: ~0.88
