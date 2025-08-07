# ❤️ Heart Stroke Prediction Web App

This is a **Machine Learning web application** built using **Streamlit** that predicts the **risk of heart stroke** based on user input medical features. The logistic regression model used in the backend has been trained and tested on healthcare data, and it provides a binary prediction: **High Risk** or **Low Risk**.

 🔍 Features

- User-friendly **web interface** built with Streamlit
- Trained with **Logistic Regression** for best accuracy
- Uses **Joblib** for model and scaler loading
- Accepts real-world features like:
  - Age, Sex, Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol Levels
  - ECG Results
  - Heart Rate, Oldpeak, and more
- Scales inputs with a pre-trained **StandardScaler**
- **One-hot encoding** ensures model-ready formatting

📁 Project Structure

```bash
├── app.py                   # Streamlit frontend app
├── LogisticRegression.pkl   # Trained model
├── heart_scaler.pkl         # StandardScaler object
├── heart_columns.pkl        # Expected input columns
├── requirements.txt         # Required Python packages
