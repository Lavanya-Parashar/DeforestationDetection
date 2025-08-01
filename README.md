# 🔥 Fire Type Classification using MODIS Satellite Data (2021–2023)

This project uses machine learning to classify fire types in India using MODIS satellite data from 2021 to 2023. The goal is to assist in real-time fire detection and improve disaster management strategies.

---

## 🎯 Project Goal

To build an accurate and efficient classification model that can identify the type of fire (e.g., forest, agricultural) based on satellite features and support rapid response systems.

---

## 🧰 Tools & Technologies Used

- Python 3.10  
- Pandas, NumPy, Scikit-learn  
- Seaborn, Matplotlib  
- SMOTE (imbalanced-learn)  
- Joblib for model saving  

---

## 🔍 Methodology

1. Data Collection from MODIS (2021–2023)
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection and Encoding
5. SMOTE for class balancing
6. Model Training (Random Forest, KNN, etc.)
7. Model Evaluation and Final Selection
8. Model Saving with Joblib

---

## ❗ Problem Statement

Manual identification of fire types from satellite data is slow and error-prone. There is a need for a machine learning model that can automate fire classification to support faster decision-making during emergencies.

---

## ✅ Solution

This project automates fire type classification using a Random Forest model trained on processed MODIS satellite data. The model uses key features like brightness, FRP, confidence, and temporal attributes to make predictions.

---

## 📦 Model File

Due to GitHub's file size limit, the trained model (`best_fire_detection_model.pkl`) is stored on Google Drive.

🔗 [Click here to download the model](https://drive.google.com/file/d/1Bopum6ORNX3UPSgtyKxiRJtyItpZcpnq/view?usp=drive_link)

> Please download and place it in the project folder before running the notebook.

---

## 📈 Model Evaluation

- Final Model: Random Forest Classifier  
- Accuracy: High accuracy on balanced test data  
- Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix  

---

## 🌏 Real-World Impact

- Supports faster identification of fire incidents  
- Reduces manual efforts in classification  
- Can be extended into live fire monitoring systems  

---


---

## 👩‍💻 Author

**Lavanya Parashar**  
AICTE Internship Project – Machine Learning  
B.Tech CSE  

