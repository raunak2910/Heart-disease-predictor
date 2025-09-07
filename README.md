❤️ Heart Disease Prediction


📌 Overview

This project predicts the likelihood of heart disease using machine learning models trained on patient data such as age, cholesterol, resting blood pressure, and exercise-related features. It demonstrates an end-to-end ML workflow — data preprocessing, model training, model saving, and deployment via a Streamlit web app.

📊 Dataset

The dataset contains patient health records with features like:

Age, RestingBP, Cholesterol, FastingBS, MaxHR, Oldpeak

Categorical features (Chest Pain Type, Resting ECG, Exercise Angina, ST Slope, etc.)

Target variable: HeartDisease (0 = No, 1 = Yes)

⚙️ Tech Stack

Python 3.12

Libraries: pandas, numpy, scikit-learn, joblib, streamlit

ML Models: Logistic Regression, Random Forest, SVM, KNN, Gradient Boosting

Deployment: Streamlit

🚀 Installation & Setup

Clone the repository and install dependencies:

git clone https://github.com/raunak2910/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py

🧠 Workflow

Data Preprocessing: One-hot encoding, scaling with StandardScaler.

Model Training: Multiple classifiers tested; best model selected.

Model Saving: joblib used to save model, scaler, and feature columns.

Deployment: Streamlit frontend allows real-time predictions.

🎯 Features

✅ Predicts heart disease risk based on patient data

✅ Multiple ML models compared for performance


✅ Scalable and modular codebase

✅ Simple and interactive Streamlit UI


📂 Project Structure

📦 heart-disease-prediction

 ┣ 📜 app.py                 # Streamlit frontend
 
 ┣ 📜 LogisticRegression_heart.pkl   # Saved ML model
 
 ┣ 📜 scaler.pkl             # StandardScaler object
 
 ┣ 📜 columns.pkl            # Feature columns used
 
 ┣ 📜 heart.csv              # Dataset
 
 ┣ 📜 requirements.txt       # Dependencies
 
 ┗ 📜 README.md              # Project documentation


🌍 Deployment

This app can be deployed on:

Streamlit Cloud

(Recommended 🚀)

Render / Heroku / Vercel (alternative options)

✨ Author: Raunak Gupta

🔗 GitHub: @raunak2910
