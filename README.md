# 🌾 Soil and Weather Based Crop Yield Prediction

This project leverages machine learning techniques to predict crop yield based on environmental factors such as soil nutrients and weather conditions. Developed as part of the Software Engineering and Project Management (SEPM) coursework at SRM Institute of Science and Technology, this solution aims to support data-driven decision-making in agriculture.

## 🔗 Google Colab Notebook
👉 [Click to Open in Google Colab](https://colab.research.google.com/drive/1a5pL2LtR1t9cBS__YHQPKgJPIv_Ujlpu?usp=sharing)

---

## 📌 Problem Statement
Accurately predicting crop yield before cultivation remains a major challenge due to diverse soil and climate conditions. This system aims to assist farmers, researchers, and planners by providing a tool that:
- Inputs real-time data
- Evaluates multiple machine learning models
- Offers yield estimates and crop recommendations

---

## 🛠️ Technologies & Tools
- Python  
- Pandas, NumPy, Seaborn, Matplotlib  
- Scikit-learn  
- LightGBM, XGBoost, SMOTE  
- Flask (for web app)  
- Google Colab (for model development)

---

## 📈 Machine Learning Models Used
- ✅ Random Forest  
- ✅ XGBoost  
- ✅ Support Vector Machine (SVM)  
- ✅ Decision Tree  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Multi-layer Perceptron (MLP)

Models were evaluated using:
- Accuracy  
- Balanced Accuracy  
- Confusion Matrix  
- Matthews Correlation Coefficient (MCC)

---

## 📊 Features
- Input parameters: Nitrogen, Phosphorus, Potassium, pH, Temperature, Humidity, Rainfall  
- Compare ML models dynamically  
- Web-based UI built using Flask  
- Export predictions (CSV/PDF)  
- SMOTE for class balancing  
- Model persistence using Pickle

---

## 📷 Screenshots

### 🔘 Web App Interface
![Web UI](https://your-image-link-if-any.png)

---

## 🚀 How to Run

### 🔧 Requirements
- Python 3.7+
- Flask
- scikit-learn
- imbalanced-learn
- pandas, numpy, seaborn, matplotlib
- lightgbm, xgboost

### 💻 Local Setup
```bash
git clone https://github.com/your-username/soil-weather-crop-yield-prediction.git
cd soil-weather-crop-yield-prediction
pip install -r requirements.txt
python app.py
