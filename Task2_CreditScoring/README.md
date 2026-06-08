# 💳 Credit Scoring Model Using Machine Learning

## 📌 Project Description

Credit scoring is an important application of Machine Learning in the banking and financial sector. It helps financial institutions determine whether a customer is likely to repay a loan or default on payments.

This project builds a Credit Scoring Model using Machine Learning algorithms to predict whether a credit card client will default on their payment in the following month.

The project includes data preprocessing, class balancing using SMOTE, model training, performance evaluation, and comparison of multiple classification algorithms.

---

## 🎯 Objectives

- Predict customer credit risk.
- Identify potential defaulters.
- Handle class imbalance using SMOTE.
- Compare multiple Machine Learning algorithms.
- Select the best performing model based on evaluation metrics.

---

## 📊 Dataset

### Dataset Used

Default of Credit Card Clients Dataset

The dataset contains customer information such as:

- Credit Limit
- Gender
- Education
- Marital Status
- Age
- Payment History
- Bill Amounts
- Previous Payment Amounts

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | No Default |
| 1 | Default Payment Next Month |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- Joblib

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Dataset Exploration
- Missing Value Checking
- Correlation Analysis
- Train-Test Split
- Feature Scaling using StandardScaler
- Class Balancing using SMOTE

---

## 📈 Exploratory Data Analysis

The project includes:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE

These visualizations help understand the data distribution and feature relationships.

---

## ⚖️ Handling Class Imbalance

The dataset contains an imbalanced target distribution.

To address this issue:

- SMOTE (Synthetic Minority Over-sampling Technique) was applied.
- Minority class samples were generated synthetically.
- Balanced data improved model learning performance.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

A statistical classification algorithm used as a baseline model.

### Support Vector Machine (SVM)

A supervised learning algorithm that separates classes using an optimal decision boundary.

### Random Forest

An ensemble learning method that combines multiple decision trees for better prediction accuracy.

### XGBoost

An advanced gradient boosting algorithm known for high predictive performance.

---

## 📏 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📊 Results

The following outputs were generated:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE
- Logistic Regression Results
- SVM Results
- Random Forest Results
- XGBoost Results
- Model Comparison Graph
- Feature Importance Graph
- Best Model Selection

Among all models, XGBoost and Random Forest achieved the best performance for credit risk prediction.

---

## 📂 Project Structure

Task2_CreditScoring

│

├── Datasets

│ └── Credit Card Default Dataset

│

├── Results

│ ├── Correlation_Matrix.png

│ ├── Class_Distribution_Before_SMOTE.png

│ ├── Class_Distribution_After_SMOTE.png

│ ├── Logistic_Regression.png

│ ├── SVM.png

│ ├── Random_Forest.png

│ ├── XGBoost.png

│ ├── Model_Comparison.png

│ ├── Feature_Importance.png

│ └── Best_Model.png

│

├── Credit_Scoring.ipynb

├── requirements.txt

└── README.md

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit Web Application
- Real-Time Credit Risk Prediction
- Financial Dashboard Integration

---

## 🎓 Learning Outcomes

Through this project:

- Credit Risk Analysis was explored.
- Class Imbalance Handling using SMOTE was implemented.
- Multiple Machine Learning algorithms were compared.
- Financial prediction techniques were studied.
- Model evaluation and selection methods were applied.

---

## ✅ Conclusion

This project demonstrates how Machine Learning can be used to predict customer credit risk. By applying data preprocessing, SMOTE balancing, and multiple classification algorithms, a reliable credit scoring system was developed. The comparison of Logistic Regression, SVM, Random Forest, and XGBoost helps identify the most effective model for predicting credit default risk.


# 💳 Credit Scoring Model Using Machine Learning

## 📌 Project Description

Credit scoring is an important application of Machine Learning in the banking and financial sector. It helps financial institutions determine whether a customer is likely to repay a loan or default on payments.

This project builds a Credit Scoring Model using Machine Learning algorithms to predict whether a credit card client will default on their payment in the following month.

The project includes data preprocessing, class balancing using SMOTE, model training, performance evaluation, and comparison of multiple classification algorithms.

---

## 🎯 Objectives

- Predict customer credit risk.
- Identify potential defaulters.
- Handle class imbalance using SMOTE.
- Compare multiple Machine Learning algorithms.
- Select the best performing model based on evaluation metrics.

---

## 📊 Dataset

### Dataset Used

Default of Credit Card Clients Dataset

The dataset contains customer information such as:

- Credit Limit
- Gender
- Education
- Marital Status
- Age
- Payment History
- Bill Amounts
- Previous Payment Amounts

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | No Default |
| 1 | Default Payment Next Month |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- Joblib

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Dataset Exploration
- Missing Value Checking
- Correlation Analysis
- Train-Test Split
- Feature Scaling using StandardScaler
- Class Balancing using SMOTE

---

## 📈 Exploratory Data Analysis

The project includes:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE

These visualizations help understand the data distribution and feature relationships.

---

## ⚖️ Handling Class Imbalance

The dataset contains an imbalanced target distribution.

To address this issue:

- SMOTE (Synthetic Minority Over-sampling Technique) was applied.
- Minority class samples were generated synthetically.
- Balanced data improved model learning performance.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

A statistical classification algorithm used as a baseline model.

### Support Vector Machine (SVM)

A supervised learning algorithm that separates classes using an optimal decision boundary.

### Random Forest

An ensemble learning method that combines multiple decision trees for better prediction accuracy.

### XGBoost

An advanced gradient boosting algorithm known for high predictive performance.

---

## 📏 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📊 Results

The following outputs were generated:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE
- Logistic Regression Results
- SVM Results
- Random Forest Results
- XGBoost Results
- Model Comparison Graph
- Feature Importance Graph
- Best Model Selection

Among all models, XGBoost and Random Forest achieved the best performance for credit risk prediction.

---

## 📂 Project Structure

Task2_CreditScoring

│

├── Datasets

│ └── Credit Card Default Dataset

│

├── Results

│ ├── Correlation_Matrix.png

│ ├── Class_Distribution_Before_SMOTE.png

│ ├── Class_Distribution_After_SMOTE.png

│ ├── Logistic_Regression.png

│ ├── SVM.png

│ ├── Random_Forest.png

│ ├── XGBoost.png

│ ├── Model_Comparison.png

│ ├── Feature_Importance.png

│ └── Best_Model.png

│

├── Credit_Scoring.ipynb

├── requirements.txt

└── README.md

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit Web Application
- Real-Time Credit Risk Prediction
- Financial Dashboard Integration

---

## 🎓 Learning Outcomes

Through this project:

- Credit Risk Analysis was explored.
- Class Imbalance Handling using SMOTE was implemented.
- Multiple Machine Learning algorithms were compared.
- Financial prediction techniques were studied.
- Model evaluation and selection methods were applied.

---

## ✅ Conclusion

This project demonstrates how Machine Learning can be used to predict customer credit risk. By applying data preprocessing, SMOTE balancing, and multiple classification algorithms, a reliable credit scoring system was developed. The comparison of Logistic Regression, SVM, Random Forest, and XGBoost helps identify the most effective model for predicting credit default risk.

# 💳 Credit Scoring Model Using Machine Learning

## 📌 Project Description

Credit scoring is an important application of Machine Learning in the banking and financial sector. It helps financial institutions determine whether a customer is likely to repay a loan or default on payments.

This project builds a Credit Scoring Model using Machine Learning algorithms to predict whether a credit card client will default on their payment in the following month.

The project includes data preprocessing, class balancing using SMOTE, model training, performance evaluation, and comparison of multiple classification algorithms.

---

## 🎯 Objectives

- Predict customer credit risk.
- Identify potential defaulters.
- Handle class imbalance using SMOTE.
- Compare multiple Machine Learning algorithms.
- Select the best performing model based on evaluation metrics.

---

## 📊 Dataset

### Dataset Used

Default of Credit Card Clients Dataset

The dataset contains customer information such as:

- Credit Limit
- Gender
- Education
- Marital Status
- Age
- Payment History
- Bill Amounts
- Previous Payment Amounts

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | No Default |
| 1 | Default Payment Next Month |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- Joblib

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Dataset Exploration
- Missing Value Checking
- Correlation Analysis
- Train-Test Split
- Feature Scaling using StandardScaler
- Class Balancing using SMOTE

---

## 📈 Exploratory Data Analysis

The project includes:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE

These visualizations help understand the data distribution and feature relationships.

---

## ⚖️ Handling Class Imbalance

The dataset contains an imbalanced target distribution.

To address this issue:

- SMOTE (Synthetic Minority Over-sampling Technique) was applied.
- Minority class samples were generated synthetically.
- Balanced data improved model learning performance.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

A statistical classification algorithm used as a baseline model.

### Support Vector Machine (SVM)

A supervised learning algorithm that separates classes using an optimal decision boundary.

### Random Forest

An ensemble learning method that combines multiple decision trees for better prediction accuracy.

### XGBoost

An advanced gradient boosting algorithm known for high predictive performance.

---

## 📏 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📊 Results

The following outputs were generated:

- Correlation Matrix
- Class Distribution Before SMOTE
- Class Distribution After SMOTE
- Logistic Regression Results
- SVM Results
- Random Forest Results
- XGBoost Results
- Model Comparison Graph
- Feature Importance Graph
- Best Model Selection

Among all models, XGBoost and Random Forest achieved the best performance for credit risk prediction.

---

## 📂 Project Structure

Task2_CreditScoring

│

├── Datasets

│ └── Credit Card Default Dataset

│

├── Results

│ ├── Correlation_Matrix.png

│ ├── Class_Distribution_Before_SMOTE.png

│ ├── Class_Distribution_After_SMOTE.png

│ ├── Logistic_Regression.png

│ ├── SVM.png

│ ├── Random_Forest.png

│ ├── XGBoost.png

│ ├── Model_Comparison.png

│ ├── Feature_Importance.png

│ └── Best_Model.png

│

├── Credit_Scoring.ipynb

├── requirements.txt

└── README.md

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit Web Application
- Real-Time Credit Risk Prediction
- Financial Dashboard Integration

---

## 🎓 Learning Outcomes

Through this project:

- Credit Risk Analysis was explored.
- Class Imbalance Handling using SMOTE was implemented.
- Multiple Machine Learning algorithms were compared.
- Financial prediction techniques were studied.
- Model evaluation and selection methods were applied.

---

## ✅ Conclusion

This project demonstrates how Machine Learning can be used to predict customer credit risk. By applying data preprocessing, SMOTE balancing, and multiple classification algorithms, a reliable credit scoring system was developed. The comparison of Logistic Regression, SVM, Random Forest, and XGBoost helps identify the most effective model for predicting credit default risk.

---


## 👤 Author

**Goutham Vinjamuri**

ML Intern | [LinkedIn Profile](https://www.linkedin.com/in/goutham-vinjamuri-902787326)

<small>Developed as part of the Machine Learning Internship at CodeAlpha.</small>

---

**📄 License**

<small>This project is open-source and available under the MIT License.</small>
