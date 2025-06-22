🧠 Predicting Customer Purchase Behavior with Logistic Regression
This project aims to predict whether a customer will purchase a product based on features like income, income type, and property ownership. The main focus is on correctly handling categorical variables using OneHotEncoder, and building a clean machine learning pipeline with logistic regression.

📊 Project Overview
Goal: Predict customer purchase behavior (1 = Bought, 0 = Did not buy)

Target Variable: Bought

Features: Income, Income Type, Owns Property

Although Income Type and Owns Property are stored as numbers, they represent categorical, non-ordinal variables — and therefore must be properly encoded to avoid misleading the model.

🔧 Tools & Libraries
pandas – data manipulation

scikit-learn – preprocessing (OneHotEncoder, StandardScaler), model training (LogisticRegression), and evaluation (accuracy, precision, recall, confusion_matrix)

statsmodels – statistical inference, p-value testing, hypothesis testing for feature significance

🧪 Key Steps
Data Cleaning & Exploration

Feature Encoding using OneHotEncoder for categorical variables

Modeling with LogisticRegression

Model Evaluation: confusion matrix, precision, recall, and accuracy

Hypothesis Testing: checking statistical significance of each variable using p-values (statsmodels)

✅ Main Insight
Only the Income feature was found to be statistically significant in predicting purchase behavior — which makes practical sense in the context of the business scenario.

📁 Files
BaseDados_RegressaoLogistica.xlsx: sample dataset

logistic_regression_model.ipynb: notebook with full pipeline and analysis

README.md: project documentation

📌 Final Note
This project highlights the importance of understanding the nature of your variables. Not all numbers represent numerical relationships — and proper preprocessing is key to building reliable models.

