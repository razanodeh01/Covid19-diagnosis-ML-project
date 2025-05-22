# 🦠 COVID-19 Diagnosis using Machine Learning (Decision Tree & ANN)


## 📌 Project Description

This machine learning project focuses on diagnosing **COVID-19** using supervised learning models. Due to privacy constraints, we were unable to access real hospital data and instead created a synthetic dataset based on local hospital procedures and indicators.  

🔍 The models classify patients as COVID-positive or negative based on symptoms and medical history.


## 🧠 Algorithms Used

### 🌳 Decision Tree Classifier
- Simple, interpretable model.
- Ideal for categorical data.

### 🧬 Artificial Neural Network (ANN)
- Multi-layer Perceptron.
- Captures complex patterns.
- More effective for numeric and continuous input.

Both models were trained using the **scikit-learn** library.


## 🛠️ Tools & Technologies

- 🐍 **Python (scikit-learn, pandas, tkinter)**.
- 📊 **WEKA 3.8.6**.
- 📈 **Custom GUI** for prediction.
- 📁 CSV-based dataset (`covid_data.csv`).


## 📊 Dataset Features

- Patient_ID  
- Age  
- Gender  
- Location  
- Symptoms: Fever, Cough, Fatigue, Loss of Taste/Smell, etc.  
- Medical History: Diabetes, Hypertension  
- COVID_Test_Result (target label)



## 🧪 Procedure & Functionality

1. **Data Preprocessing**: Label encoding, train-test split
2. **Model Training**: Separate classifiers for DT and ANN
3. **Evaluation**: Accuracy, precision, etc. shown using WEKA and Python
4. **Prediction GUI**: Users can enter symptoms and get predictions from both models


## 🧬 Results Summary

| Model         | Tool Used      | Accuracy Insight |
|---------------|----------------|------------------|
| Decision Tree | Python & WEKA  | Fast, interpretable |
| ANN (MLP)     | Python (sklearn) | High accuracy, better with more data |

✅ Observation: Increasing training data improves model generalization.

## 🔴 Live Demo
You can see the COVID-19 prediction tool live here:
[Run](https://github.com/user-attachments/assets/45c60590-27a1-4491-a79f-ce8d5a723f0d)


## 👥 Group Members
- [**Razan Abdelrahman**](https://github.com/razanodeh01) 
- [**Lana Hamayel**](https://github.com/lanaHamayel5)

> 💬 *“More data leads to smarter models — and better care.”*
