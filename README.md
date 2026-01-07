📌 Project Overview

The Tobacco Use and Mortality (2004–2015) project is a machine learning–based data science application that analyzes the impact of tobacco consumption on mortality rates. The project uses multiple healthcare datasets related to smoking prevalence, hospital admissions, medical prescriptions, and fatalities to predict mortality risk and identify key contributing factors.

The objective of this project is to apply supervised machine learning techniques to uncover patterns in tobacco usage and evaluate their influence on public health outcomes.

🎯 Project Objectives

Analyze tobacco usage trends over time

Understand the relationship between smoking and mortality

Perform exploratory data analysis (EDA)

Build and evaluate machine learning models

Identify key features influencing mortality

Support public health insights through data-driven analysis

🗂️ Dataset Description

The project uses the following datasets:

Dataset Name	Description
smokers.csv	Smoking prevalence data
admissions.csv	Hospital admissions related to tobacco use
prescriptions.csv	Medical prescriptions for smoking-related diseases
fatalities.csv	Mortality data caused by tobacco use
metrics.csv	Additional health and system metrics

All datasets are merged using a common attribute (Year) to create a unified dataset for analysis.

🛠️ Tools and Technologies
Programming Language

Python

Development Tools

Jupyter Notebook

VS Code

Libraries Used

pandas

numpy

matplotlib

seaborn

scikit-learn

⚙️ Project Workflow

Data Collection and Loading

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Train–Test Split

Model Training

Model Evaluation

Feature Importance Analysis

Result Interpretation

🤖 Machine Learning Models Used

Logistic Regression

Random Forest Classifier

The problem is treated as a binary classification task, where the target variable is mortality risk.

📊 Model Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Random Forest Classifier showed better overall performance compared to Logistic Regression.

📈 Results Summary

Tobacco usage is strongly correlated with mortality rates

Hospital admissions and smoking prevalence are key predictors

Random Forest achieved higher accuracy and better generalization

🔮 Future Enhancements

Integration of SHAP/LIME for explainability

Deployment using Flask or Streamlit

Inclusion of demographic and lifestyle data

Real-time prediction system

⚖️ Ethical Considerations

No personal or identifiable health data was used

All datasets are anonymized and aggregated

The project complies with ethical data usage practices

▶️ How to Run the Project

Install required Python libraries

Open Jupyter Notebook

Place all CSV files in the project directory

Run the notebook cell by cell

📚 References

World Health Organization (WHO)

National Health Service (NHS)

Centers for Disease Control and Prevention (CDC)
