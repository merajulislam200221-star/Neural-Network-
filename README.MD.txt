Objective
The objective of this project is to build a Machine Learning model using Logistic Regression to predict whether a customer will subscribe to a term deposit.
The model classifies the output into:
•	Yes (1) → Customer subscribes 
•	No (0) → Customer does not subscribe 
Dataset Description
The dataset is related to bank marketing campaigns and contains customer information.
Dataset Files
•	bank.csv 
•	bank-full.csv (larger dataset) 
 Features Include:
•	Age 
•	Job 
•	Marital Status 
•	Education 
•	Balance 
•	Housing Loan 
•	Contact Type 
•	Campaign Details 
•	Previous Outcomes 
Target Variable:
•	y → Indicates whether the customer subscribed (yes / no) 
 Methodology
 Step 1 – Data Loading
•	Dataset is uploaded using Google Colab 
•	Extracted from ZIP file 
•	Loaded using Pandas 

 Step 2 – Data Preprocessing
 Handling Categorical Data:
•	Used Label Encoding to convert categorical columns into numeric values 

Step 3 – Train-Test Split
•	Dataset split into 80% training and 20% testing 

Step 4 – Model Building
A Logistic Regression model is used for classification.

Step 5 – Model Evaluation
Model performance is evaluated using:
•	Accuracy Score 
•	Confusion Matrix 




 Result
•	The model predicts whether a customer will subscribe to a term deposit. 
•	Accuracy score indicates how well the model performs on unseen data. 
•	Confusion matrix shows correct and incorrect predictions. 

 Interpretation
•	Logistic Regression works well for binary classification problems 
•	Performance depends on: 
o	Data quality 
o	Feature selection 
o	Class balance 

Conclusion
Logistic Regression is an effective and simple algorithm for predicting customer behavior in marketing campaigns.
It provides a baseline model for classification tasks and helps in understanding customer decision patterns

