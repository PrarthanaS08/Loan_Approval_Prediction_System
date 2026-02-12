# Loan Approval Prediction System (Machine Learning + Streamlit)

A Machine Learning based web application that predicts whether a loan will be Approved ✅ or Rejected ❌ based on customer details such as income, credit history, education, marital status, employment type, loan amount, and property area.

The project is deployed as an interactive Streamlit web app that also generates a mini loan statement with date/time and allows users to download it.

# Features

✅ Predict loan approval instantly
✅ User-friendly Streamlit UI
✅ Encodes categorical inputs automatically
✅ Generates a Mini Loan Statement
✅ Download statement as .txt file
✅ Clean UI with footer & profile links

# Machine Learning Workflow

✅ Data preprocessing (handling categorical values)
✅ Feature encoding (Gender, Married, Property Area, etc.)
✅ Model training using Scikit-learn
✅ Model saved as .pkl file
✅ Model loaded into Streamlit app for real-time prediction

# Tech Stack

✅ Python
✅ Streamlit
✅ NumPy
✅ Pandas
✅ Scikit-learn
✅ Seaborn
✅ Pickle

# 📂 Project Structure

📁 Loan-Prediction-Project/
│── app.py
│── model.ipynb
│── dataset.csv
│── loan_model.pkl
│── requirements.txt
│── README.md

# How It Works

1. User enters customer details in the Streamlit UI
2. The input is converted into numerical form using encoding
3. The saved ML model (loan_model.pkl) predicts the result
4. The system displays Approved/Rejected
5. A mini loan statement is generated
6. The statement can be downloaded as a .txt file

# Future Improvements

✨ Add model accuracy + evaluation metrics in UI
✨ Add feature scaling and pipelines
✨ Deploy online using Streamlit Cloud / Render
✨ Add more models & compare results
✨ Improve UI design with charts and insight
