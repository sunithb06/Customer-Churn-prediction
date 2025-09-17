# Customer-Churn-prediction
Customer Churn Prediction using Artificial Neural Networks applies deep learning to analyze customer behavior and transaction data, predicting which users are at risk of leaving. This helps businesses improve retention by identifying and acting on churn signals early.


## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses. This project predicts whether a customer is likely to churn (leave) based on their historical data.  
We use **TensorFlow** to build and train a neural network classifier on the **Telco Customer Churn dataset**.

## 🧠 Key Features
- Data preprocessing (handling missing values, encoding categorical variables)
- Feature scaling using **StandardScaler**
- Neural network model built with **TensorFlow/Keras**
- Model evaluation using:
  - **Confusion Matrix**
  - **Accuracy Score**
  - **Classification Report**
- Visualizations with **Seaborn** and **Matplotlib**

## 📂 Dataset
We use the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn).  
Key columns include:
- **Demographics:** gender, SeniorCitizen, Partner, Dependents  
- **Services:** PhoneService, InternetService, StreamingTV, etc.  
- **Account Info:** Contract type, PaymentMethod, MonthlyCharges, TotalCharges  
- **Target:** Churn (Yes/No)

## ⚙️ Tech Stack
- **Python 3.x**
- **TensorFlow/Keras**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**

## 🏗️ Project Workflow
1. **Load & Clean Data:** Handle missing values, encode categorical features  
2. **Feature Scaling:** Standardize numerical columns  
3. **Train-Test Split:** Split data into 80-20 train/test sets  
4. **Model Building:** Build a neural network with multiple dense layers  
5. **Model Training:** Compile and train the model using Adam optimizer  
6. **Evaluation:** Calculate accuracy, generate confusion matrix & classification report  
7. **Visualization:** Plot results for better insights  


