
# Heart Attack Analysis Prediction

#### Heart Attack Analysis &amp; Prediction model created for DataTalks.Club mlzoomcamp course midterm project
<p align="center">
<img src="https://cdn.dribbble.com/users/2154580/screenshots/6452241/atemlos_loop_heart_v1.0_chriseff_dribbble.gif" width="500" height="400" />
</p>


It is classification model created to predict whether the patient has chance of getting heart attack or not based on the clinical parameters. Deployed in streamlit cloud.
Created using Kaggle noteboook

Dataset: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

Kaggle link: https://www.kaggle.com/code/kavya2099/heart-attack-analysis-prediction/notebook

Link to access streamlit: https://heart-attack-analysis-prediction.streamlit.app/

<p align="center">
<img src="predict heart attack.gif"  />
</p>

## Introduction

Heart disease is a major health concern worldwide, accounting for a significant number of deaths each year. Early detection and prevention are crucial in managing this condition. Machine learning models offer a promising approach to predicting the likelihood of heart attacks based on clinical parameters. In this study, we have developed a classification model to predict whether a patient is at risk of experiencing a heart attack based on their clinical parameters.

## Problem Statement

The aim of this study is to develop a reliable classification model that can predict the likelihood of a patient experiencing a heart attack based on their clinical parameters. By accurately identifying individuals at risk, healthcare providers can intervene early with targeted interventions and lifestyle modifications to reduce the risk of heart disease and improve patient outcomes.

**Code flow**

        * Data processing
        * EDA
        * Feature Engineering
        * Scaling and Normalization
        * Model Selection and Evaluation
        * Test the model
        * Deploying the model

**Data**

Input the below information to check whether the patient has risk of heart attack or not

Age : Age of the patient

Sex: The person’s sex (1 = male, 0 = female)


cp: chest pain type

— Value 0: asymptomatic

— Value 1: atypical angina

— Value 2: non-anginal pain

— Value 3: typical angina


trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)

chol: The person’s cholesterol measurement in mg/dl

fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

restecg: resting electrocardiographic results

— Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria

— Value 1: normal

— Value 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)

thalach: The person’s maximum heart rate achieved

exang: Exercise induced angina (1 = yes; 0 = no)

oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the ECG plot. See more here)

slope: the slope of the peak exercise ST segment — 0: downsloping; 1: flat; 2: upsloping

ca: The number of major vessels (0–3)

thal: A blood disorder called thalassemia 

Value 0: NULL (dropped from the dataset previously

Value 1: fixed defect (no blood flow in some part of the heart)

Value 2: normal blood flow

Value 3: reversible defect (a blood flow is observed but it is not normal)

target: Heart disease (1 = no, 0= yes)


## Things implemented

- Exploratory Data Analysis
- Finding **Mutual information** with the target feature
- Applying **Decision tree classification, Random forest classifiaction and XGB classification** algorithms with different feature parameters and picking up the best model based on AUC score and accuracy
- Used **Matplotlib and Seaborn Heatmap** for visualization
  
## Deploying model

* Implemented the model in **Streamlit**.
* XGB Model will predict whether a patient is at risk of experiencing a heart attack based on their clinical parameters.

## Things to try it out next!
* Applying crossvalidation concepts in model training
* Applying Pipeline concepts in model training
* Trying out other Feature selection methods
* Using Z scores to treat outliers
* Applying other classification algorithms
* Implementing more EDA concepts

## References:

https://towardsdatascience.com/heart-disease-uci-diagnosis-prediction-b1943ee835a7

🫀📊 Cardiac Health Risk Prediction ❤️🔍🩺
📌 Overview
Cardiovascular diseases remain one of the leading causes of death worldwide. Early detection is essential to improve patient outcomes and reduce mortality rates.
This project leverages Machine Learning to predict the risk of heart attack using clinical and diagnostic parameters.
The model helps healthcare providers and patients identify potential risks early, enabling timely preventive measures and lifestyle modifications.

🎯 Problem Statement
The goal of this project is to develop a robust classification model that predicts whether a patient is at high risk of experiencing a heart attack based on their medical attributes.
By integrating data analysis, feature engineering, and predictive modeling, this system aims to provide reliable insights for proactive healthcare interventions.

🖥️ Project Summary
This is a classification model designed to determine whether a patient is likely to have a heart attack based on their clinical parameters.

Developed using a Kaggle Notebook for data exploration, model building, and evaluation.

Deployed on Streamlit Cloud for easy web-based accessibility and real-time predictions.

Dataset Source: Heart Attack Analysis & Prediction Dataset – Kaggle

Original Kaggle Notebook: Click Here

🔄 Workflow / Code Flow
Data Collection & Processing – Cleaning and preparing the dataset for analysis.

Exploratory Data Analysis (EDA) – Understanding patterns, trends, and correlations.

Feature Engineering – Creating and selecting the most impactful features.

Scaling & Normalization – Standardizing data for model compatibility.

Model Selection & Evaluation – Comparing algorithms like Decision Tree, Random Forest, and XGBoost based on accuracy & AUC score.

Model Testing – Validating the best model on unseen data.

Deployment – Deploying the model using Streamlit for real-time predictions.

🧮 Dataset Features
Age – Patient’s age

Sex – Gender (1 = male, 0 = female)

Chest Pain Type (cp) – 0: asymptomatic, 1: atypical angina, 2: non-anginal pain, 3: typical angina

Resting Blood Pressure (trestbps) – in mm Hg

Cholesterol (chol) – in mg/dl

Fasting Blood Sugar (fbs) – 1: true (>120 mg/dl), 0: false

Resting ECG (restecg) – 0: LV hypertrophy, 1: normal, 2: ST-T wave abnormality

Max Heart Rate (thalach) – maximum achieved during exercise

Exercise Induced Angina (exang) – 1: yes, 0: no

ST Depression (oldpeak) – relative to rest

Slope of ST Segment (slope) – 0: downsloping, 1: flat, 2: upsloping

Major Vessels (ca) – number of major vessels (0–3)

Thalassemia (thal) – 1: fixed defect, 2: normal flow, 3: reversible defect

Target – 1: no disease, 0: heart disease present

🚀 Features & Highlights
✅ Multiple ML Models – Decision Tree, Random Forest, and XGBoost for comparison
✅ Performance Optimization – Best model selected based on AUC score & accuracy
✅ Mutual Information Analysis – Identify features with the strongest predictive power
✅ Data Visualization – Interactive plots & heatmaps with Matplotlib & Seaborn
✅ Streamlit Deployment – Web-based interface for real-time predictions
✅ Scalable Code Structure – Easy to expand with new features and algorithms

🛠️ Tech Stack & Libraries
Languages: Python 🐍

ML Frameworks: scikit-learn, XGBoost

Visualization: Matplotlib, Seaborn

Data Processing: Pandas, NumPy

Deployment: Streamlit

📈 Future Improvements
🔹 Apply cross-validation during model training for more robust performance
🔹 Implement Pipeline for streamlined preprocessing & modeling
🔹 Explore additional feature selection methods
🔹 Handle outliers using statistical methods like Z-score
🔹 Experiment with other advanced classification algorithms
🔹 Integrate more interactive visualizations for insights

