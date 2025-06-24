# -PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

COMPANY: CODTECH IT SOLUTIONS

NAME: PRISCILLA M

INTERN ID: CT04DN1650

DOMAIN: DATA ANALYSIS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

*Accident Severity Prediction using Machine Learning*

The main objective was to build a classification model to predict the severity of car accidents using structured features from a real-world dataset. 

The task involved complete ML pipeline steps: preprocessing, feature engineering, model training, evaluation, and comparison.

*Dataset Description*

Name: Combined Accident Dataset (2022–2023)

Format: CSV

Size: 1000+ records

Target Variable: severity (categorical: Minor, Moderate, Severe)

Features: Demographic info, vehicle type, engine size, location, weather, etc.

*Tools & Libraries Used*
Python (Jupyter Notebook)

pandas, numpy for data handling

matplotlib, seaborn for visualization

scikit-learn for modeling and evaluation

xgboost for advanced boosting classifier


1. Data Inspection
   
Loaded the dataset and checked for nulls and duplicates.

Verified that the dataset was clean (no nulls or duplicates).

2. Feature Engineering
   
Categorical features were encoded using LabelEncoder.

Target variable severity was label-encoded.

Applied StandardScaler for feature scaling on numerical columns.

Split the dataset into 80% train and 20% test using train_test_split.

3. Model Building
   
Tested the following models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Each model was trained on the same train-test split for fair comparison.

4. Evaluation
   
Evaluated models using accuracy_score, confusion_matrix, and classification_report.

XGBoost achieved the highest accuracy of ~40%, outperforming other models on this dataset.

Model performances were visualized using bar plots.

5. Model Comparison
   
A bar chart comparing model accuracies clearly showed that XGBoost had the best performance in predicting accident severity.

Key Insights

Building a predictive model involved a systematic pipeline, from handling missing values to tuning model parameters.

XGBoost showed potential by outperforming simpler models.

Feature encoding and scaling were crucial steps before applying machine learning algorithms.

Understanding the nature of your target variable and exploring the data thoroughly improves model interpretability.

*Output*

![Image](https://github.com/user-attachments/assets/1a3476b6-ddc6-4b81-b13d-eb1de29ed459)

![Image](https://github.com/user-attachments/assets/cd24c21d-9ba8-4820-bd7a-e5e590581f5a)

![Image](https://github.com/user-attachments/assets/7f921417-f764-4fdc-aba5-d88f8ac2193a)
