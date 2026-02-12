# Loan Approval Prediction System (Machine Learning + Streamlit)

A Machine Learning based web application that predicts whether a loan will be Approved ✅ or Rejected ❌ based on customer details such as income, credit history, education, marital status, employment type, loan amount, and property area.

The project is deployed as an interactive Streamlit web app that also generates a mini loan statement with date/time and allows users to download it.

# Features

✅ Predict loan approval instantly <br>
✅ User-friendly Streamlit UI <br>
✅ Encodes categorical inputs automatically <br>
✅ Generates a Mini Loan Statement <br>
✅ Download statement as .txt file <br>
✅ Clean UI with footer & profile links <br>

# Machine Learning Workflow

✅ Data preprocessing (handling categorical values) <br>
✅ Feature encoding (Gender, Married, Property Area, etc.) <br>
✅ Model training using Scikit-learn <br>
✅ Model saved as .pkl file <br>
✅ Model loaded into Streamlit app for real-time prediction <br>

# Tech Stack

✅ Python <br>
✅ Streamlit<br>
✅ NumPy <br>
✅ Pandas <br>
✅ Scikit-learn <br>
✅ Seaborn <br>
✅ Pickle <br>

# 📂 Project Structure

📁 Loan-Prediction-Project/ <br>
│── app.py <br>
│── model.ipynb <br>
│── dataset.csv <br>
│── loan_model.pkl <br>
│── requirements.txt <br>
│── README.md <br>

# How It Works

1. User enters customer details in the Streamlit UI
2. The input is converted into numerical form using encoding
3. The saved ML model (loan_model.pkl) predicts the result
4. The system displays Approved/Rejected
5. A mini loan statement is generated
6. The statement can be downloaded as a .txt file

# Future Improvements

✨ Add model accuracy + evaluation metrics in UI <br>
✨ Add feature scaling and pipelines <br>
✨ Deploy online using Streamlit Cloud / Render <br>
✨ Add more models & compare results <br>
✨ Improve UI design with charts and insight <br>

# Developed By

### Prarthana S
📧 Email: prarthanas0308@gmail.com <br>
🔗 LinkedIn: https://www.linkedin.com/in/prarthanas03/
