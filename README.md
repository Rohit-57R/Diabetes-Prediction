# 🩺 Diabetes Prediction Web App

A Machine Learning-based web application that predicts whether a person is diabetic or not using health-related parameters. The application is built using **Python**, **Scikit-Learn**, and **Streamlit**.

---

## 🚀 Features

✅ Predicts diabetes based on user input

✅ Interactive and user-friendly web interface

✅ Machine Learning model trained using diabetes dataset

✅ Real-time prediction using Streamlit

✅ Fast and lightweight application

---

## 🛠️ Technologies Used

- 🐍 Python
- 📊 NumPy
- 🤖 Scikit-Learn
- 🎨 Streamlit
- 💾 Pickle

---

## 📂 Project Structure

```text
Diabetes-Prediction/
│
├── app.py
├── predictive_system.py
├── trained_model.sav
├── requirements.txt
└── README.md
```

---

## 📋 Input Parameters

The model predicts diabetes based on the following medical attributes:

| Feature | Description |
|----------|------------|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose level |
| Blood Pressure | Blood pressure value |
| Skin Thickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| Diabetes Pedigree Function | Genetic diabetes score |
| Age | Age of the person |

---


---

## 🎯 How It Works

1. User enters medical information.
2. Input data is processed.
3. Trained Machine Learning model analyzes the data.
4. Application predicts:
   - 🟢 Not Diabetic
   - 🔴 Diabetic

---


## 🧠 Machine Learning Model

The project uses a trained **Support Vector Machine (SVM)** model saved as:

```text
trained_model.sav
```

The model is loaded using Python's Pickle library and used for real-time predictions.

---

## 📈 Future Improvements

- 📊 Display prediction probability
- ☁️ Deploy on Streamlit Cloud
- 📱 Mobile-friendly UI
- 📉 Data visualization dashboard
- 🔐 User authentication

---



## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub!
