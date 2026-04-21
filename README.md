# 🏥 Heart Disease Prediction from Medical Data

## CodeAlpha Machine Learning Internship — Task 4

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat)](https://xgboost.readthedocs.io)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)](https://matplotlib.org)

---

## 📌 Objective

Build a machine learning system to predict the presence of heart disease in a patient using clinical medical data. Multiple classification algorithms are compared and evaluated to identify the best performing model.

---

## 🛠️ Algorithms Used

| Algorithm | Type |
|---|---|
| Logistic Regression | Linear Classifier |
| Support Vector Machine (SVM — RBF Kernel) | Kernel-based |
| Random Forest | Ensemble — Bagging |
| XGBoost | Ensemble — Boosting |

---

## 📊 Dataset

- **Source:** UCI Heart Disease Dataset (Cleveland)
- **Records:** 1,025 patient records
- **Features:** 13 medical attributes
- **Target:** `0` = No Heart Disease, `1` = Heart Disease Present

| Feature | Description |
|---|---|
| age | Age of the patient |
| sex | Gender (1 = Male, 0 = Female) |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting ECG results (0–2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thalassemia type |

---

## 📁 Project Structure

```
CodeAlpha_DiseasePrediction/
├── image/
│   ├── confusion matrix.png
│   ├── feature analysis.png
│   ├── feature importance.png
│   ├── heatmap.png
│   ├── model comparison.png
│   └── target distribution.png
├── notebook/
│   └── disease_prediction (1).ipynb
├── .gitignore
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 How to Run

**Option 1 — Google Colab (Recommended)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rosesharma13/CodeAlpha_DiseasePrediction/blob/main/notebook/disease_prediction%20(1).ipynb)

**Option 2 — Local Setup**

```bash
git clone https://github.com/Rosesharma13/CodeAlpha_DiseasePrediction.git
cd CodeAlpha_DiseasePrediction
pip install -r requirements.txt
jupyter notebook notebook/disease_prediction\ \(1\).ipynb
```

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Target Distribution
![Target Distribution](image/target%20distribution.png)
Class balance between heart disease positive and negative patients.

---

### 🔹 Feature Analysis
![Feature Analysis](image/feature%20analysis.png)
Distribution of key medical features across the dataset.

---

### 🔹 Correlation Heatmap
![Heatmap](image/heatmap.png)
Relationships between features help identify the most predictive medical attributes.

---

## 🤖 Model Building & Comparison

### 🔹 Model Comparison
![Model Comparison](image/model%20comparison.png)
All four models trained and compared using Accuracy, F1-Score, and ROC-AUC.

---

## 🌲 Best Model Insights

### 🔹 Feature Importance
![Feature Importance](image/feature%20importance.png)
Most influential medical features driving the prediction decision.

---

### 🔹 Confusion Matrix
![Confusion Matrix](image/confusion%20matrix.png)
Classification performance showing true positives, false positives, and error distribution.

---

## 📈 Results

- Four models benchmarked — best selected via ROC-AUC cross-validation
- Confusion matrix analysis on best performing model
- Feature importance reveals most predictive clinical attributes
- Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

---

## 🔮 Future Improvements

- Hyperparameter tuning with GridSearchCV
- Deploy as Streamlit web application
- Add SHAP values for model explainability
- Test on larger real-world clinical datasets

---

## 🙌 Acknowledgements

- Dataset: UCI Machine Learning Repository — Heart Disease Dataset
- Built as part of CodeAlpha Machine Learning Internship — Task 4

---

## 👩‍💻 Author

**Rose Sharma** | CodeAlpha ML Internship

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rose-sharma13)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rosesharma13)
