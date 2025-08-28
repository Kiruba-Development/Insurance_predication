
🧠
# Insurance Response Prediction using XGBoost
📌 
# Project Overview
This project aims to predict whether a user will respond positively to an automobile insurance offer using a classification model built with XGBoost. The dataset contains user demographics, vehicle information, and historical insurance data.

📊
# Dataset Features
# Feature	Description
id	Unique identifier
Gender	Gender of the user
Age	Age of the user
Driving_License	Whether the user has a driving license
Region_Code	Encoded region information
Previously_Insured	Whether the user was previously insured
Vehicle_Age	Age category of the vehicle (transformed)
Vehicle_Damage	History of vehicle damage (transformed)
Annual_Premium	Premium amount
Policy_Sales_Channel	Sales channel code
Vintage	Days since the user joined
Response	Target variable (1 = will stay, 0 = will not)
🧹 
# Data Preprocessing
Transformed Vehicle_Age and Vehicle_Damage columns.
Handled missing values and encoded categorical features.
Balanced the dataset using scale_pos_weight = 7.9 based on class distribution.
⚙️ 
# Model Training
Used XGBoostClassifier for training.
Performed hyperparameter tuning using GridSearchCV to find optimal parameters.
Achieved accuracy > 88% and strong ROC AUC performance.
📈 Evaluation
Metrics used:
Accuracy
ROC Curve & AUC
Confusion Matrix
