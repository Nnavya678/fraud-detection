
# 💳 Fraud Detection System
## 🚀 Overview
This project is a machine learning-based fraud detection system that predicts whether a transaction is fraudulent or not. It uses historical transaction data to train a model and provides real-time predictions through an interactive Streamlit web application.

## 🧠 Model Details
- Algorithm Used: Logistic Regression  
- Problem Type: Binary Classification  
- Target Variable: isFraud (1 = Fraud, 0 = Non-Fraud)
- Handles class imbalance using class weighting  
- Preprocessing done using ColumnTransformer (scaling + encoding)

## 📊 Features Used  
- type → Type of transaction   
- amount → Transaction amount  
- oldbalanceOrg → Sender balance before transaction  
- newbalanceOrig → Sender balance after transaction  
- oldbalanceDest → Receiver balance before transaction  
- newbalanceDest → Receiver balance after transaction  

## 🖥️ Streamlit App
Run locally:
```
streamlit run fraud_detection.py
```

## 📦 Tech Stack
* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

## 📁 Project Structure
* fraud_detection.py → Main application
* analysis_model.ipynb → Model training
* Fraud_detection_pipeline.pkl → Saved model
* requirements.txt → Dependencies

## 📌 Dataset
kaggle link: https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download

## 🔮 Future Improvements
* Improve model accuracy
* Deploy online
* Add dashboard and visualization

## 📌 Conclusion
This project demonstrates how machine learning can help detect fraudulent transactions and reduce financial risks.

## 📊 Results
- Accuracy: 95%  
- Precision (Fraud Class): 2%  
- Recall (Fraud Class): 94%  
- F1-Score (Fraud Class): 4% 

## 👤 Author
**Navya Goyal**

