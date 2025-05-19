  <h1>🧠 Breast Cancer Prediction App</h1>

  <p>This Streamlit web application predicts whether a breast mass is <strong>benign or malignant</strong> based on cytological measurements. It uses a machine learning model trained on the Breast Cancer Wisconsin dataset.</p>

  <h2>✨ Features</h2>
  <ul>
    <li><strong>Interactive Sidebar</strong>: Manually adjust 30 cytology-based features using sliders.</li>
    <li><strong>Radar Chart Visualization</strong>: Visualizes mean, standard error, and worst-case values.</li>
    <li><strong>ML-Powered Prediction</strong>: Classifies the mass and provides benign/malignant probability.</li>
    <li><strong>Styled Output</strong>: Diagnosis results are color-coded for easy interpretation.</li>
    <li><strong>Model Training Script</strong>: Includes script to train and export the model and scaler.</li>
  </ul>

  <h2>🧪 Machine Learning Details</h2>
  <ul>
    <li><strong>Model</strong>: Logistic Regression</li>
    <li><strong>Data</strong>: Breast Cancer Wisconsin (Diagnostic) dataset</li>
    <li><strong>Preprocessing</strong>: Features scaled using StandardScaler</li>
    <li><strong>Evaluation</strong>: Achieves high accuracy on test set</li>
  </ul>

  <h2>📁 Project Structure</h2>
  <pre>
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
  </pre>

  <h2>📷 Image Examples</h2>

  <h3>Example of Benign Prediction</h3>
  <img src="https://github.com/user-attachments/assets/a373ae7b-f00c-43c7-af71-da27677cd5ba" alt="Example 1 - Benign Prediction" width="600">

  <h3>Example of Malignant Prediction</h3>
  <img src="https://github.com/user-attachments/assets/9f794a0b-1892-4175-8495-b57a8dde90ee" alt="Example 2 - Malignant Prediction" width="600">

  <h2>⚠️ Disclaimer</h2>
  <blockquote>
    This app is intended for <strong>educational or assistive purposes only</strong>. It should not be used as a substitute for professional medical diagnosis.
  </blockquote>

  <hr>
  <p>Feel free to contribute or modify for personal or research use.</p>

</body>
</html>
