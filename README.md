# 🌱 Soil Nutrient Prediction using Spectral Data

## 📌 Project Overview
This project was developed as part of **HackNuthon 6.0**, organized by **Nirma University** 🏆. It utilizes a **Transformer-based model** to predict soil **pH levels** using spectral reflectance data. The dataset consists of various spectral wavelengths and soil properties collected at different water levels (0ml, 25ml, 50ml). 

## 🚀 Features
- Uses **Deep Learning (Transformer Model)** for accurate soil pH prediction.
- Implements **feature engineering** with spectral indices.
- Supports **multi-water level analysis** for better soil assessment.
- Provides **visualizations** of spectral trends.

## 📂 Dataset
The dataset includes:
- **Spectral Reflectance Data** (Wavelengths: 435nm, 460nm, 560nm, 680nm, 705nm, 860nm)
- **Soil Properties** (pH levels, Nitrogen content, etc.)
- **Water Level Variations** (0ml, 25ml, 50ml)

## 🏗 Model Architecture
The model is based on a **Transformer Encoder**, which processes spectral features and predicts the soil pH level. The key components include:
- **Embedding Layer**: Converts input features into high-dimensional space.
- **Transformer Encoder**: Captures feature relationships.
- **Regression Head**: Outputs the final pH prediction.

## 🔧 Installation
Clone the repository and install dependencies:
```sh
 git clone https://github.com/your-repo-link.git
 cd soil-nutrient-prediction
 pip install -r requirements.txt
```

## 📊 Training & Evaluation
To train and evaluate the model, run:
```sh
python train.py
```

## 📈 Results & Insights
- **Achieved high R² value** for soil pH prediction.
- **Water level variations impact spectral readings**.
- **Certain wavelengths like 460nm and 860nm play a key role** in prediction accuracy.

## 📌 Future Improvements
✅ Add more spectral indices.
✅ Fine-tune Transformer hyperparameters.
✅ Explore additional soil properties.

## 💡 Contributors

- **Team Name: Data Pirates** 🏴‍☠️
- **Bhimani Yatra** 👩‍💻
- **Drashti Vaghasiya, Harvy Doshi, Heli Detroja** 👨‍💻

## 📜 License
This project is licensed under the MIT License.

🌟 _Feel free to contribute and improve this project!_ 🚀
