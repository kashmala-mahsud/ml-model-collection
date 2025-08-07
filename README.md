🤖 ML Model Collection

A curated collection of beginner to intermediate-level Machine Learning projects built with Python, scikit-learn, and Streamlit. This repository includes:

* 🩺 Heart Disease Prediction
* 🏦 Loan Prediction App
* 😄 Emotion Prediction

All projects are designed to be modular, reproducible, and beginner-friendly, complete with notebooks, trained models, and UI deployment.

---

## 📂 Projects Overview

### 1. 💓 Heart Disease Prediction

Predicts the likelihood of heart disease based on 13 key medical inputs using a **Logistic Regression** model and a deployed **Streamlit** app.

🔗 [Project Folder](./heart-disease-prediction)

### 2. 🏦 Loan Prediction App

Classifies whether a loan should be approved or not using customer details like income, credit history, etc. Trained using **Random Forest** and deployed using Streamlit.

🔗 [Project Submodule](./Loan-Prediction-App)

### 3. 😄 Emotion Prediction

Classifies the emotional tone of a given sentence into categories like *joy*, *sadness*, *anger*, and *fear* using NLP preprocessing and **Multinomial Naive Bayes**.

🔗 [Project Submodule](./emotion-prediction)

---

## 🧪 Tech Stack

* Python 3.x
* scikit-learn
* pandas, numpy
* joblib / pickle
* Streamlit
* CountVectorizer / TFIDF (for NLP)

---

## 🚀 How to Use

```bash
# Clone this repository
git clone https://github.com/kashmala-mahsud/ml-model-collection.git
cd ml-model-collection

# Navigate to any project folder
cd heart-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

---

## 🔗 Submodule Setup (if cloning with submodules)

If using submodules:

```bash
git clone --recurse-submodules https://github.com/kashmala-mahsud/ml-model-collection.git
```

Or initialize manually:

```bash
git submodule update --init --recursive
```

---

## 👩‍💻 Author

**Kashmala Mahsud**
📎 [GitHub](https://github.com/kashmala-mahsud)

