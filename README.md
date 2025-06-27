# 🩺 Revolutionizing Liver Care: Predicting Liver Cirrhosis using Advanced Machine Learning

## 📘 Project Overview

This project applies machine learning techniques to accurately predict **liver cirrhosis** using patient clinical data. The goal is to assist healthcare professionals in early diagnosis and intervention, reducing the risks associated with late-stage liver diseases.

## 🎯 Objectives

- Predict liver cirrhosis status based on patient data
- Improve diagnostic speed and accuracy using ML
- Develop a user-friendly web interface for prediction
- Contribute to AI-powered medical tools

## 🧪 Dataset

- **Source**: UCI Machine Learning Repository – Liver Cirrhosis dataset
- **Features**: Age, Gender, Albumin, Bilirubin, Alkaline Phosphatase, etc.
- **Target**: Liver disease status (Yes/No)

## 🛠️ Technologies Used

- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Streamlit
- **ML Models**: Logistic Regression, Random Forest, Decision Tree, KNN
- **Deployment**: Streamlit Web App

## 📂 Project Structure

liver-cirrhosis-prediction/ ├── liver_cirrhosis_prediction.ipynb ├── liver_data.csv ├── app.py ├── model.pkl ├── requirements.txt └── README.md

## 🔍 Exploratory Data Analysis (EDA)

- Null value handling and data cleaning
- Correlation heatmaps and feature distribution
- Outlier detection using boxplots
- Feature scaling and encoding

## 🤖 Machine Learning Models

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 83%     |
| Random Forest       | 88%     |
| Decision Tree       | 84%     |
| KNN                 | 80%     |

✅ Best Model: **Random Forest Classifier**

## 🖥️ Web Application

Built using **Streamlit** for easy user interaction:

### How to Run:

```bash
pip install -r requirements.txt
streamlit run app.py

Then visit: http://localhost:8501

📸 Sample Output

Input fields for patient clinical data

Model prediction: "Liver Cirrhosis Detected" or "No Cirrhosis Detected"

Visualization: Bar chart / Pie chart for prediction confidence (optional)


🧱 System Architecture

[User Input] → [Streamlit Frontend] → [Trained ML Model] → [Prediction Output]

📌 Key Features

Fast and accurate predictions

Simple and intuitive UI

Easily customizable with new datasets or models


🔗 GitHub Repository

🔗 https://github.com/Chennampalliaswini/Revotionzing-liver-care-Predicting-liver-cirrhosis-using-advanced-machine-learning-techniques

🙋‍♀️ Submitted By

Chennampalli Aswini


