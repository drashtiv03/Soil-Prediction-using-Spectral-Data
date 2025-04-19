## 🌱 Soil Nutrient Prediction Using Spectral Data
A machine learning project aimed at predicting various soil nutrient levels using spectral reflectance data. This project employs multiple ML models to accurately determine pH, Nitrogen (Nitro), Potassium (Pota Nitro), and other nutrient levels based on spectral data at specific wavelengths.

## 👨‍💻 Team: Data Pirates
**Contributors**: Drashti Vaghasiya, Bhimani Yatra, Drashti Vaghasiya, Heli Detroja

## 🧠 Project Overview
The goal of this project is to predict nutrient levels in soil using spectral reflectance values. Each nutrient or metric is predicted using a different machine learning model selected based on its predictive power and accuracy for that task.

## 🧪 Nutrient Predictions & Models Used

| **Nutrient**     | **Model Used**                            | **Ideal Wavelengths (nm)**         |
|------------------|--------------------------------------------|-------------------------------------|
| pH               | Transformer Encoder Model (Self-Attention) | 435, 460, 560, 705, 860, 680        |
| Nitro            | Random Forest Regressor                   | 645, 705, 680, 585, 560             |
| Pota Nitro (1)   | Gradient Boosting Regressor               | 410, 460, 510                       |
| Pota Nitro (2)   | Neural Network with Multi-Head Attention  | 410, 460, 510                       |
| Posh Nitro       | Fully Connected Regression Head           | 460, 860                            |


## 📈 Results Summary
Each model is evaluated with three sample test conditions:

**Concentration Levels** : 0ml, 25ml, 50ml

**Evaluation Metrics**: Regression metrics (MAE, RMSE, R² score, etc.)

## 🔧 Project Architecture
**Data Input**: Spectral data (reflectance at different wavelengths)

**Preprocessing**: Feature selection based on ideal wavelengths

**Model Training**: Separate models trained for each nutrient

**Prediction Output**: Continuous values representing nutrient concentration

**Post-processing**: Normalization and interpretation of predicted values

## 🧠 Technologies Used
Python

Scikit-learn

TensorFlow / PyTorch

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebooks

## 📌 Future Improvements
Add cross-validation and hyperparameter tuning
Integrate explainability using SHAP or LIME
Build a web-based dashboard for farmer usage
Expand model to additional nutrients or environmental factors
