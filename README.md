# Titanic_Survival_Predictor
A machine learning project that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related features. This notebook uses classic classification models and includes feature engineering, EDA, and model evaluation.

---

## 📊 Project Overview

This project explores the Titanic dataset and applies classification models to predict survival. We implemented:
- Data cleaning and preprocessing
- Feature engineering (like extracting titles and family size)
- Model training with Decision Tree, Random Forest, and Logistic Regression
- Cross-validation and evaluation metrics
- Model saving with `pickle`

---

## 🧠 ML Models Used
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

---

## 📁 Files Included
- `titanic_survival-Copy1.ipynb` – Main Jupyter notebook with all code
- `titanic_model.pkl` – Trained Random Forest model
- `titanic.csv` – Dataset (if not public, mention where to get it)
- `requirements.txt` – Python package dependencies

▶️ How to Run
Clone the repository

Make sure you have titanic.csv in the same folder

Run the notebook: titanic_survival_eda.ipynb

The model will be trained and saved as titanic_model.pkl

📈 Results
Achieved high accuracy using Random Forest

Cross-validation score shows consistent performance

Feature engineering like title extraction boosted accuracy

---
📚 Dataset Source
Kaggle - Titanic: Machine Learning from Disaster

🙌 Credits
Project by Manav Bhuta
Guided with Scikit-Learn and Titanic dataset

📌 Future Ideas
GUI or Streamlit web app

Hyperparameter tuning

Add more ensemble models (XGBoost, etc.)

## 📦 Requirements

Install dependencies with:
```bash
pip install -r requirements.txt


