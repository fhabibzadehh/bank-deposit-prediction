# bank-deposit-prediction
The dataset contains information about customers of a Portuguese bank. The goal of the model is to predict whether a customer will subscribe to a term deposit or not.

**Key steps in the project:**

1)Data cleaning and preprocessing

2)One-hot encoding for categorical features

3)Scaling numerical features

4)Splitting data into train/test

5)Building a Logistic Regression model with class_weight='balanced'

6)Evaluating model performance

7)Analyzing feature importance

**Dataset**

File: bank.csv

Target Variable:
deposit → converted into target (1 = yes, 0 = no)

**Methods & Tools**
Python, Pandas, NumPy
Scikit-Learn
OneHotEncoder, StandardScaler
Logistic Regression (balanced class weight)
Matplotlib & Seaborn for visualization

**Preprocessing**

Handled categorical features using OneHotEncoder
Scaled numeric features using StandardScaler
Combined preprocessing using ColumnTransformer
Used Pipeline to streamline training
