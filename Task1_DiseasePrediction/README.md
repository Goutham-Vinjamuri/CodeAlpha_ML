# Disease Prediction Using Machine Learning

## 📌 Project Description

This project predicts the likelihood of Diabetes using Machine Learning algorithms. The objective is to assist in early disease detection by analyzing patient health parameters and comparing multiple classification models.

The project includes data preprocessing, class balancing using SMOTE, model training, evaluation, and performance comparison.

---

## 🎯 Objectives

- Predict diabetes based on patient medical data.
- Handle class imbalance using SMOTE.
- Compare multiple machine learning algorithms.
- Evaluate model performance using standard metrics.
- Select the best-performing model.

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | Non-Diabetic |
| 1 | Diabetic |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- Google Colab

---

## 🔄 Data Preprocessing

The following preprocessing techniques were applied:

- Dataset exploration
- Statistical analysis
- Correlation analysis
- Train-Test Split
- Feature Scaling using StandardScaler
- Class Balancing using SMOTE

---

## 🤖 Machine Learning Algorithms

The following models were trained and evaluated:

### 1. Logistic Regression
A simple and effective binary classification algorithm.

### 2. Support Vector Machine (SVM)
Creates an optimal decision boundary between classes.

### 3. Random Forest
An ensemble learning method based on multiple decision trees.

### 4. XGBoost
A powerful gradient boosting algorithm known for high predictive performance.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## ⚖ Handling Class Imbalance

The dataset contained an unequal distribution of diabetic and non-diabetic samples.

To solve this problem:

- SMOTE (Synthetic Minority Over-sampling Technique) was applied.
- The minority class was balanced in the training dataset.
- Model performance improved after balancing.

---

## 📈 Project Results

The project includes:

- Correlation Matrix Analysis
- Class Distribution Before SMOTE
- Class Distribution After SMOTE
- Logistic Regression Results
- SVM Results
- Random Forest Results
- XGBoost Results
- Model Comparison Graph
- Best Model Selection

---

## 📁 Project Structure

Task1_DiseasePrediction/

├── Disease_Prediction.ipynb

├── diabetes.csv

├── requirements.txt

├── README.md

└── Results/

    ├── Best model - Diabetes.png
    
    ├── Class Distribution_Before_SMOTE.png
    
    ├── Class Distribution_After_SMOTE.png
    
    ├── Logistic Regression.png
    
    ├── SVM.png
    
    ├── Random Forest.png
    
    ├── XGBoost.png
    
    ├── Model_Comparison.png
    
    └── correlation matrix.png

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Deployment using Streamlit
- Integration of additional disease prediction modules
- Real-time prediction system

---

## 🎓 Learning Outcomes

Through this project:

- Machine Learning classification techniques were implemented.
- Class imbalance handling using SMOTE was performed.
- Multiple models were compared and analyzed.
- Healthcare prediction systems were explored using real-world data.

---

## ✅ Conclusion

This project successfully demonstrates the use of Machine Learning in healthcare analytics. Multiple classification algorithms were trained and evaluated for diabetes prediction. SMOTE was used to handle class imbalance, and model comparison helped identify the most effective prediction model.

The project highlights the importance of data preprocessing, model evaluation, and comparative analysis in building reliable healthcare prediction systems.
