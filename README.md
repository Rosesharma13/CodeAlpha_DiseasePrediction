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

Build a machine learning system to predict the presence of heart disease in a patient using clinical medical data. The goal is to compare multiple classification algorithms and identify the best performing model based on key evaluation metrics.

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
- **Note:** Dataset is loaded automatically in the notebook

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
| exang | Exercise induced angina (1 = Yes) |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thalassemia type |

---

## 📁 Project Structure

```
CodeAlpha_DiseasePrediction/
├── notebook/
│   └── disease_prediction.ipynb    ← Main notebook
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 How to Run

**Option 1 — Google Colab (Recommended, no setup needed)**

Click → [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rosesharma13/CodeAlpha_DiseasePrediction/blob/main/notebook/disease_prediction.ipynb)

**Option 2 — Local Setup**

```bash
# 1. Clone the repo
git clone https://github.com/Rosesharma13/CodeAlpha_DiseasePrediction.git
cd CodeAlpha_DiseasePrediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run notebook
jupyter notebook notebook/disease_prediction.ipynb
```

---

## 📊 Exploratory Data Analysis (EDA)

The dataset was explored to understand feature distributions, class balance, and correlations between medical attributes and heart disease presence.

Key EDA steps:
- Feature distribution analysis by target class
- Correlation heatmap across all 13 features
- Missing value check and data type validation
- Class balance verification

---

## 🤖 Model Building & Comparison

Four classification models were trained and evaluated:

- **Preprocessing:** StandardScaler for feature normalization
- **Train/Test Split:** 80/20
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC

---

## 📈 Results

- Multiple models compared using accuracy and F1-score
- Best model selected based on cross-validated ROC-AUC score
- Confusion matrix analysis performed for the top model
- Feature importance analysis reveals most predictive medical attributes

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Deploy as a Streamlit web application
- Add SHAP values for model explainability
- Test on larger, real-world clinical datasets

---

## 🙌 Acknowledgements

- Dataset: UCI Machine Learning Repository — Heart Disease Dataset
- Built as part of CodeAlpha Machine Learning Internship — Task 4

---

## 👩‍💻 Author

**Rose Sharma** | CodeAlpha ML Internship

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rose-sharma13)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rosesharma13)
