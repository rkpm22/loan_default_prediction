# Loan Default Prediction Machine Learning Project

 
## 📌 Overview
This project focuses on predicting loan default status using machine learning techniques. The goal is to preprocess financial data, train classification models, and evaluate their performance in identifying high-risk loan applicants. The workflow includes data cleaning, feature engineering, categorical encoding, model training with Random Forest and XGBoost, and performance evaluation.



## 📂 Dataset
Source: Loan_Default.csv
Size: 148,670 samples with 34 features
Key Features:

loan_amount, Credit_Score, income, age, loan_purpose, Region, term, LTV, etc.

Target variable: Status (1 = Default, 0 = Non-Default)

## 🔧 Technologies Used
- **Python**: Primary programming language
- **Pandas, NumPy**: Data manipulation and preprocessing
- **Matplotlib, Seaborn, Plotly**: Data visualization
- **Scikit-learn**: Machine learning algorithms and preprocessing
- **XGBoost, RandomForestClassifier**: Model training and evaluation

## 📂 Dataset Description
The dataset includes borrower details such as income, credit history, and past loan behavior. Key steps include:
- Handling missing values
- Encoding categorical variables
- Feature scaling using `RobustScaler`
- Splitting data into training and testing sets

## 📊 Exploratory Data Analysis (EDA)
EDA was performed using visualization libraries to:
- Understand distributions of loan default behavior
- Identify correlations between features
- Detect outliers and patterns in the dataset

## 🚀 Model Training & Evaluation
Two machine learning models were trained:
1. **Random Forest Classifier** 
2. **XGBoost Classifier** 

### **Evaluation Metrics**
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix for visualizing true vs. false predictions
- Feature Importance Analysis using XGBoost

### **Model Performance**
- The **XGBoost model** achieved high accuracy and provided better insights via feature importance analysis.
- The **Confusion Matrix** showed a balanced classification performance.

## 🔍 Key Insights from Analysis
Imbalanced Classes: Only ~24.6% of loans defaulted (Status = 1).
Critical Features: Credit_Score, loan_amount, and income showed strong correlations with the target.
Age Impact: Borrowers aged 45-54 were the largest demographic.

## 🔮 Future Improvements
- Hyperparameter tuning for better performance
- Inclusion of additional features to improve model generalization
- Exploring deep learning approaches for further optimization


👨💻 Author: Raunaksingh Khalsa
🔗 Repository: https://github.com/rkpm22/loan_default_prediction/tree/main
📧 Contact: raunaksinghkhalsa@gmail.com
