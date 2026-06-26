# NovaGen Health Risk Prediction

A Machine Learning project focused on building a supervised classification pipeline to identify whether individuals have a generally healthy profile or are at higher health risk. Developed for **NovaGen Research Labs**, this system leverages population health records to automate participant selection for clinical trials and longitudinal health studies.

---

## 📌 Project Overview

Biomedical research often requires screening thousands of volunteers through medical exams, lifestyle assessments, and clinical tests. This project builds a predictive model that classifies individuals into **"Healthy"** or **"Unhealthy"** profiles using a combination of numerical and categorical health indicators. 

### Key Objectives
* **Clinical Trial Eligibility:** Streamline the selection of eligible participants for medical studies.
* **Risk-Based Stratification:** Group populations accurately for downstream risk analysis and outcome comparison.

---

## 📊 Dataset Description

The model is trained on a comprehensive dataset containing **9,800 unique individual health records** to ensure independent observations without sampling bias.

### Features Covered
* **Physiological Indicators:** Age, Body Mass Index (BMI), Blood Pressure (Systolic mmHg), Cholesterol (mg/dL), Glucose Level (mg/dL), Resting Heart Rate (bpm).
* **Lifestyle Factors:** Average Sleep Hours, Average Exercise Hours, Daily Water Intake (litres), Smoking Habits, Alcohol Consumption, Diet Category.
* **Medical & Mental Attributes:** Stress Level (1–10 scale), Mental Health Score, Physical Activity Level, Medical History, and Allergies.
* **Engineered/Encoded Variables:** One-hot encoded columns for Diet Types (`Vegan`, `Vegetarian`) and Blood Groups (`AB`, `B`, `O`).
* **Target:** Binary classification label indicating the health outcome / risk status.

---

## 📂 Repository Structure

```text
├── novagen.ipynb                  # Main Jupyter Notebook with data processing & ML models
├── Supervised ML _Assignment5.pdf # Project requirements and problem definition
└── README.md                      # Project documentation
