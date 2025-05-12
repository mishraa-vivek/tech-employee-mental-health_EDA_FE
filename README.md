# 🧠 tech-employee-mental-health_EDA_FE

This project explores a dataset focused on the mental health of tech employees. The goal is to analyze survey data to understand the factors that influence whether an individual seeks treatment for mental health issues. The analysis includes exploratory data analysis (EDA), data preprocessing, and plans for machine learning modeling.


## 📁 Project Structure

├── PredictingMentalHealthIssuesinTechEmployees.ipynb # Main analysis notebook
├── README.md # Project overview
└── survey.csv # Dataset (not included due to size/privacy)

---

## 📊 Dataset Overview

The dataset includes reported information from tech industry employees, covering topics such as:

- **Demographics**: Age, gender
- **Workplace environment**: Company size, work benefits, culture
- **Mental health background**: Family history, willingness to talk, previous treatment
- **Target variable**: `treatment` — whether the respondent has sought treatment for mental health issues

Most features are **categorical**, with `Age` being the only numerical variable.

---

## 🎯 Project Objectives

- 📌 Load and explore the dataset
- 📌 Understand feature distributions and detect missing values
- 📌 Analyze patterns linked to seeking treatment
- 📌 Clean the data for modeling
- 📌 Build and evaluate a predictive model (future step)

---

## 🧪 Exploratory Data Analysis (EDA)

The EDA section performs:

- Null value visualization using `sns.heatmap`
- Distribution plots of `Age`
- Bar plots showing how different features relate to the `treatment` target
- Feature-wise missingness analysis
