![image](https://github.com/user-attachments/assets/28339d2d-099b-43cb-8d9a-b43c5de4c91e)
![image](https://github.com/user-attachments/assets/9ae819cf-feb7-4d95-b553-7e44acf84580)


# ANN_CLLASIFICATION_CHRUN
This project predicts customer churn in a banking environment using an Artificial Neural Network (ANN). It leverages Streamlit for interactive user input, Scikit-learn for preprocessing, and TensorFlow/Keras for model development and deployment.

🔍 Problem Statement
Customer churn—when users stop using a service—is a critical metric for businesses. This project helps banks predict if a customer is likely to leave, enabling targeted retention strategies.

🚀 Features

🎯 Binary classification of customer churn (Yes/No)
🧰 Preprocessing with LabelEncoder, OneHotEncoder, and StandardScaler
🧠 ANN model built and trained with TensorFlow/Keras
📦 Pre-trained model loading (model.h5) for fast inference
🌐 Interactive web UI using Streamlit
📊 Real-time predictions based on user input

🧩 Technologies Used
Python 🐍
TensorFlow
Keras (via TensorFlow)
Scikit-learn
Pandas, NumPy
Streamlit
Pickle (for encoder and scaler persistence)
#Project Structure
├── ann.py                    # Main Streamlit app
├── model.h5                 # Trained ANN model
├── scaler                   # StandardScaler object (Pickle)
├── one                      # OneHotEncoder object (Pickle)
├── label_encoder_gender     # LabelEncoder for 'Gender' (Pickle)
└── README.md

💡 How to Run
1.Install dependencies:
bash: pip install -r requirements.txt
2.Run the Streamlit app:
bash:streamlit run ann.py
3.Enter customer data and get an instant churn prediction!

📈 Sample Input Features
Credit Score
Geography (One-Hot Encoded)
Gender (Label Encoded)
Age
Tenure
Account Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary

🛠 Future Improvements
Model performance evaluation (accuracy, AUC)
Improved UI/UX with visual insights
Integration with live customer databases



