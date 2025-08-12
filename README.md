---

# 🫀📊 **Cardiac Health Risk Prediction** ❤️🔍🩺

## 📌 Overview

Cardiovascular diseases remain one of the leading causes of death worldwide. Early detection is essential to improve patient outcomes and reduce mortality rates.
This project leverages **Machine Learning** to **predict the risk of heart attack** using clinical and diagnostic parameters.
The model helps healthcare providers and patients identify potential risks early, enabling timely preventive measures and lifestyle modifications.

---

## 🎯 Problem Statement

The goal of this project is to develop a **robust classification model** that predicts whether a patient is at high risk of experiencing a heart attack based on their medical attributes.
By integrating **data analysis, feature engineering, and predictive modeling**, this system aims to provide reliable insights for proactive healthcare interventions.

---

## 🖥️ Project Summary

This is a **classification model** designed to determine whether a patient is likely to have a heart attack based on their clinical parameters.

* Developed using a **Kaggle Notebook** for data exploration, model building, and evaluation.
* Deployed on **Streamlit Cloud** for easy web-based accessibility and real-time predictions.
* Dataset Source: [Heart Attack Analysis & Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)
* Original Kaggle Notebook: [Click Here](https://www.kaggle.com/code/kavya2099/heart-attack-analysis-prediction/notebook)

---

## 🔄 Workflow / Code Flow

1. **Data Collection & Processing** – Cleaning and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)** – Understanding patterns, trends, and correlations.
3. **Feature Engineering** – Creating and selecting the most impactful features.
4. **Scaling & Normalization** – Standardizing data for model compatibility.
5. **Model Selection & Evaluation** – Comparing algorithms like Decision Tree, Random Forest, and XGBoost based on accuracy & AUC score.
6. **Model Testing** – Validating the best model on unseen data.
7. **Deployment** – Deploying the model using **Streamlit** for real-time predictions.

---

## 🧮 Dataset Features

* **Age** – Patient’s age
* **Sex** – Gender (1 = male, 0 = female)
* **Chest Pain Type (cp)** – 0: asymptomatic, 1: atypical angina, 2: non-anginal pain, 3: typical angina
* **Resting Blood Pressure (trestbps)** – in mm Hg
* **Cholesterol (chol)** – in mg/dl
* **Fasting Blood Sugar (fbs)** – 1: true (>120 mg/dl), 0: false
* **Resting ECG (restecg)** – 0: LV hypertrophy, 1: normal, 2: ST-T wave abnormality
* **Max Heart Rate (thalach)** – maximum achieved during exercise
* **Exercise Induced Angina (exang)** – 1: yes, 0: no
* **ST Depression (oldpeak)** – relative to rest
* **Slope of ST Segment (slope)** – 0: downsloping, 1: flat, 2: upsloping
* **Major Vessels (ca)** – number of major vessels (0–3)
* **Thalassemia (thal)** – 1: fixed defect, 2: normal flow, 3: reversible defect
* **Target** – 1: no disease, 0: heart disease present

---

## 🚀 Features & Highlights

✅ **Multiple ML Models** – Decision Tree, Random Forest, and XGBoost for comparison
✅ **Performance Optimization** – Best model selected based on **AUC score & accuracy**
✅ **Mutual Information Analysis** – Identify features with the strongest predictive power
✅ **Data Visualization** – Interactive plots & heatmaps with Matplotlib & Seaborn
✅ **Streamlit Deployment** – Web-based interface for real-time predictions
✅ **Scalable Code Structure** – Easy to expand with new features and algorithms

---

## 🛠️ Tech Stack & Libraries

* **Languages:** Python 🐍
* **ML Frameworks:** scikit-learn, XGBoost
* **Visualization:** Matplotlib, Seaborn
* **Data Processing:** Pandas, NumPy
* **Deployment:** Streamlit

---

## 📈 Future Improvements

🔹 Apply **cross-validation** during model training for more robust performance
🔹 Implement **Pipeline** for streamlined preprocessing & modeling
🔹 Explore **additional feature selection** methods
🔹 Handle **outliers** using statistical methods like Z-score
🔹 Experiment with other advanced **classification algorithms**
🔹 Integrate **more interactive visualizations** for insights

---

## References:

https://towardsdatascience.com/heart-disease-uci-diagnosis-prediction-b1943ee835a7
