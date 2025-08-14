# 🩺 Diabetes Prediction using Machine Learning

## 📌 Overview
This project is an **end-to-end Machine Learning pipeline** for predicting the likelihood of a patient having diabetes based on medical parameters. It uses the **Pima Indians Diabetes Dataset** and demonstrates how to clean, preprocess, train, evaluate, and save an ML model for deployment.

Healthcare professionals can use such models as **decision-support tools** to identify high-risk patients early, enabling timely lifestyle changes and medical intervention.

---

## 📊 Dataset
- **Source**: [Pima Indians Diabetes Dataset (UCI / Kaggle)](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**:
  - `Pregnancies` - Number of times pregnant
  - `Glucose` - Plasma glucose concentration
  - `BloodPressure` - Diastolic blood pressure (mm Hg)
  - `SkinThickness` - Triceps skin fold thickness (mm)
  - `Insulin` - 2-Hour serum insulin (mu U/ml)
  - `BMI` - Body mass index
  - `DiabetesPedigreeFunction` - Diabetes pedigree function
  - `Age` - Age in years
- **Target**:
  - `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Features of the Project
- Data Cleaning & Missing Value Imputation
- Feature Scaling
- Model Training with:
  - Logistic Regression
  - Random Forest Classifier
- Model Evaluation using:
  - Accuracy, Precision, Recall, F1-Score
  - ROC-AUC Score
  - Confusion Matrix
- ROC Curve Visualization
- Feature Importance Analysis
- Hyperparameter Tuning using GridSearchCV
- Model Saving & Loading using `joblib`
- Example prediction on new patient data

---

## 🛠️ Tech Stack
- **Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `joblib`

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/diabetes-prediction-ml.git
cd diabetes-prediction-ml
