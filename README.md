# 🩺 Diabetes Prediction with Machine Learning

This project predicts diabetes using the Pima Indians Diabetes Dataset with classical Machine Learning algorithms.

## 📊 Dataset
- **Source**: Pima Indians Diabetes Dataset (Kaggle)
- **Features**: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target**: Outcome (0 = No Diabetes, 1 = Diabetes)

## ⚙️ Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Joblib (save model)
- Streamlit (demo)

## 🚀 Workflow
1. Data exploration & cleaning
2. Preprocessing & scaling
3. Model training (Logistic Regression, Random Forest, XGBoost)
4. Evaluation: Accuracy, Precision, Sensitivity, Specificity, F1, ROC-AUC
5. Feature importance
6. Save and reuse best model

## ✅ Results
- Best model: Random Forest (example)
- ROC-AUC: 0.85
- Sensitivity: 0.80
- Specificity: 0.75

## 📂 Project Structure
- data/diabetes.csv
- notebooks/Diabetes_Prediction.ipynb
- requirements.txt
- README.md
- .gitignore

## 🎯 Goal
Predicting whether or not a person has diabetes using medical information (age, glucose level, blood pressure, BMI, etc.).

This is a binary classification problem:
- 0 → Does not have diabetes
- 1 → Has diabetes
