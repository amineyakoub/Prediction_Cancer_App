🧠 Breast Cancer Prediction App

This Streamlit web application predicts whether a breast mass is benign or malignant based on cytological measurements. It uses a machine learning model trained on the Breast Cancer Wisconsin dataset.

✨ Features

Interactive Sidebar: Manually adjust 30 cytology-based features using sliders.

Radar Chart Visualization: Visualizes mean, standard error, and worst-case values.

ML-Powered Prediction: Classifies the mass and provides benign/malignant probability.

Styled Output: Diagnosis results are color-coded for easy interpretation.

Model Training Script: Includes script to train and export the model and scaler.

🧪 Machine Learning Details

Model: Logistic Regression

Data: Breast Cancer Wisconsin (Diagnostic) dataset

Preprocessing: Features scaled using StandardScaler

Evaluation: Achieves high accuracy on test set

📁 Project Structure

App_Predict_Cancer/
│
├── app/
│   └── main.py           # Streamlit app script
│
├── model/
│   ├── main.py           # Model training script
│   ├── model.pkl         # Saved trained model
│   └── scaler.pkl        # Saved feature scaler
│
├── data/
│   └── data.csv          # Breast cancer dataset
│
├── assets/
│   └── style.css         # Custom CSS styling
│
├── Image_results/
│   ├── exemple_1.png
│   └── exemple_2.png

⚠️ Disclaimer

This app is intended for educational or assistive purposes only. It should not be used as a substitute for professional medical diagnosis.

Feel free to contribute or modify for personal or research use.

