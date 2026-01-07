🩺 Tobacco Use and Mortality (2004–2015)








Machine Learning Project

📌 Overview

The Tobacco Use and Mortality (2004–2015) project is a data science and machine learning application that examines the relationship between tobacco consumption and mortality rates. Using multiple healthcare datasets, the project applies supervised learning techniques to predict mortality risk and identify key factors contributing to smoking-related deaths.

This project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model building, evaluation, and interpretation.


❓ Problem Statement

To predict mortality risk based on tobacco usage patterns and associated healthcare indicators using machine learning models.

🎯 Objectives

Analyze tobacco consumption trends over time

Study the impact of smoking on mortality

Perform exploratory data analysis (EDA)

Build and compare classification models

Identify important predictors of mortality

Support public health insights using data-driven methods


🗂️ Datasets

The following datasets are used in this project:

<img width="758" height="278" alt="image" src="https://github.com/user-attachments/assets/b19561d0-3cd6-49c4-800d-2f83816d49d1" />


All datasets are merged using the Year column to form a unified dataset.

🛠️ Tech Stack

Language: Python

IDE: Jupyter Notebook, VS Code

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn


⚙️ Project Workflow
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering & Scaling
      ↓
Train–Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Result Interpretation


🤖 Machine Learning Models

Logistic Regression

Random Forest Classifier

The task is formulated as a binary classification problem, where mortality risk is predicted.


📊 Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

The Random Forest Classifier achieved superior performance compared to Logistic Regression.


📈 Results

Strong correlation found between tobacco use and mortality

Hospital admissions and smoking prevalence are key predictors

Random Forest model demonstrated better accuracy and robustness


🧠 Conclusion

This project confirms that machine learning techniques can effectively analyze and predict mortality related to tobacco use. The results emphasize the severe impact of smoking on public health and provide insights that can assist healthcare planning and policy formulation.


🔮 Future Enhancements

Add explainable AI techniques (SHAP, LIME)

Deploy the model using Flask or Streamlit

Integrate demographic and lifestyle features

Use real-time or regional healthcare data


⚖️ Ethical Considerations

No personal or identifiable data was used

All datasets are aggregated and anonymized

Ethical standards for health data analysis were maintained


▶️ How to Run

Install required Python libraries

Place all CSV files in the project directory

Open the Jupyter Notebook

Run all cells sequentially
