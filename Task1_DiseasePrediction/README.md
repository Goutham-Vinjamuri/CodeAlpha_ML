# Disease Prediction Using Machine Learning

## 📌 Project Description

This project predicts the likelihood of Diabetes using Machine Learning algorithms. The objective is to assist in early disease detection by analyzing patient health parameters and comparing multiple classification models.

The project includes data preprocessing, class balancing using SMOTE, model training, evaluation, and performance comparison.

---

## 🎯 Objectives

- Predict diabetes based on patient medical data
- Handle class imbalance using SMOTE
- Compare multiple machine learning algorithms
- Evaluate model performance using standard metrics
- Select the best-performing model

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

### Features (8 Input Variables)

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
|-------|---------|
| 0 | Non-Diabetic |
| 1 | Diabetic |

---

## 🛠 Technologies Used

- Python 3.7+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- Jupyter Notebook / Google Colab

---

## 🔄 Data Preprocessing Pipeline

The following preprocessing techniques were applied:

1. Dataset exploration & statistical analysis
2. Correlation analysis
3. Train-Test Split (80-20)
4. Feature Scaling using StandardScaler
5. Class Balancing using SMOTE

---

## 🤖 Machine Learning Algorithms

### 1. Logistic Regression
A simple and effective binary classification algorithm, good for baseline performance.

### 2. Support Vector Machine (SVM)
Creates an optimal decision boundary between classes, effective for high-dimensional data.

### 3. Random Forest
An ensemble learning method based on multiple decision trees, captures non-linear patterns.

### 4. XGBoost
A powerful gradient boosting algorithm known for high predictive performance and efficiency.

---

## 📊 Evaluation Metrics

Models were evaluated using:

- **Accuracy Score** - Overall prediction correctness
- **Precision** - Ratio of true positives to predicted positives
- **Recall** - Ratio of true positives to actual positives
- **F1-Score** - Harmonic mean of precision and recall
- **ROC-AUC Score** - Area under ROC curve
- **Confusion Matrix** - Detailed breakdown of predictions

---

## ⚖ Handling Class Imbalance

**Problem:** The dataset contained an unequal distribution of diabetic and non-diabetic samples.

**Solution:** Applied SMOTE (Synthetic Minority Over-sampling Technique)
- Generated synthetic samples for the minority class
- Balanced the training dataset
- Improved model robustness and fairness

---

## 📈 Project Outputs

The project generates:

- ✅ Correlation Matrix Analysis
- ✅ Class Distribution Before SMOTE
- ✅ Class Distribution After SMOTE
- ✅ Individual Model Results (Logistic Regression, SVM, Random Forest, XGBoost)
- ✅ Model Comparison Graph
- ✅ Best Model Selection

---

## 📁 Project Structure

```
Task1_DiseasePrediction/
│
├── Disease_Prediction.ipynb
├── diabetes.csv
├── requirements.txt
├── README.md
│
└── Results/
    ├── Best_Model_Diabetes.png
    ├── Class_Distribution_Before_SMOTE.png
    ├── Class_Distribution_After_SMOTE.png
    ├── Logistic_Regression.png
    ├── SVM.png
    ├── Random_Forest.png
    ├── XGBoost.png
    ├── Model_Comparison.png
    └── correlation_matrix.png
```

---

## 🚀 Getting Started

### Installation

```bash
pip install -r requirements.txt
```

### Running the Project

```bash
jupyter notebook Disease_Prediction.ipynb
```

Execute all cells to generate models, predictions, and visualizations.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Deployment using Streamlit web application
- Integration of additional disease prediction modules
- Real-time prediction system
- Model explainability (SHAP/LIME)
- Cross-validation for robustness testing

---

## 🎓 Learning Outcomes

Through this project:

- ✅ Machine Learning classification techniques implementation
- ✅ Class imbalance handling using SMOTE
- ✅ Multi-model evaluation and comparison
- ✅ Healthcare prediction systems development
- ✅ Real-world data analysis and insights

---

## ✅ Conclusion

This project successfully demonstrates the application of Machine Learning in healthcare analytics. By implementing multiple classification algorithms, handling class imbalance with SMOTE, and performing rigorous model evaluation, we developed a reliable diabetes prediction system.

The comparative analysis of Logistic Regression, SVM, Random Forest, and XGBoost highlights the importance of model evaluation in selecting the most effective prediction approach.

---

## 👤 Author

**Goutham Vinjamuri**

ML Intern | [LinkedIn Profile](https://www.linkedin.com/in/goutham-vinjamuri-902787326)

Developed as part of the Machine Learning Internship at CodeAlpha.

---
## 📄 License
 
This project is open-source and available under the MIT License.
---



