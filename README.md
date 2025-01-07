# Student-Dropout-Risk-Predictor
This project focuses on predicting student dropout risk using a Random Forest Classifier. By analyzing academic performance and behavioral data, such as grades, study time, failures, and absences, the model identifies students who are at high risk of dropping out. The system also includes an interactive component that allows users to input student information and receive personalized predictions, enabling proactive interventions to support at-risk students. The reason I used a Random Forest Classifier is because this gained the highest accuracy among other models we tested with an accuracy score of 0.92.


Key Features

1. Data Preparation: 
The target variable dropout_risk is generated based on subject grades (G1, G2, G3), marking students with at least one grade below 10 as high risk.

2. Feature Selection: 
Relevant features include grades (G1, G2, G3), studytime, failures, and absences.

3. Data Preprocessing: 
Dummy encoding for categorical variables (if any).
Feature standardization using StandardScaler.

4. Model Training: 
A Random Forest Classifier is trained with 100 estimators.

5. User Interaction: 
A CLI-based user input system predicts dropout risk for custom student data.

