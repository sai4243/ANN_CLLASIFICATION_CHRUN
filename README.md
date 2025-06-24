![image](https://github.com/user-attachments/assets/28339d2d-099b-43cb-8d9a-b43c5de4c91e)
![image](https://github.com/user-attachments/assets/9ae819cf-feb7-4d95-b553-7e44acf84580)

# 🧠 ANN Customer Churn Prediction

This project predicts customer churn in a banking environment using an **Artificial Neural Network (ANN)**. It leverages **Streamlit** for an interactive UI, **Scikit-learn** for preprocessing, and **TensorFlow/Keras** for model development and deployment.

---

## 🔍 Problem Statement

Customer churn—when users stop using a service—is a critical metric for businesses. This project enables banks to predict whether a customer is likely to leave, allowing them to take proactive retention actions.

---

## 🚀 Features

- 🎯 Binary classification of customer churn (Yes/No)
- 🧰 Preprocessing using `LabelEncoder`, `OneHotEncoder`, and `StandardScaler`
- 🧠 ANN model built and trained with TensorFlow/Keras
- 📦 Pre-trained model loading (`model.h5`) for fast inference
- 🌐 Real-time web interface with Streamlit
- 📊 Instant churn predictions based on user input

---

## 🧩 Technologies Used

- Python 🐍
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Streamlit
- Pickle (for encoder and scaler persistence)

---

## 📁 Project Structure
├── app.py # Main Streamlit application
├── model.h5 # Trained ANN model
├── scaler.pkl # StandardScaler object (Pickle)
├── onehot_encoder_geo.pkl # OneHotEncoder for 'Geography' (Pickle)
├── label_encoder_gender.pkl # LabelEncoder for 'Gender' (Pickle)
├── requirements.txt # Required Python packages
└── README.md # Project documentation


---

## 💡 How to Run the Project

1. **Install dependencies:**

```bash
pip install -r requirements.txt

streamlit run app.py


