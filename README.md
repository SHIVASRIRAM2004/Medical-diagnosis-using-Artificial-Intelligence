# 🏥 Medical Diagnosis Using AI

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

An AI-powered web application that predicts multiple medical conditions
using machine learning models trained on real-world datasets.

---

## 🔍 Diseases Covered

| Disease              | Algorithm Used        | Dataset               |
|----------------------|-----------------------|-----------------------|
| Diabetes             | Machine Learning      | diabetes_data.csv     |
| Heart Disease        | Machine Learning      | heart_disease_data.csv|
| Parkinson's Disease  | Machine Learning      | parkinson_data.csv    |
| Thyroid Disease      | Machine Learning      | hypothyroid.csv       |
| Lung Cancer          | Machine Learning      | survey lung cancer.csv|

---

## 🚀 Features

- Multi-disease prediction from a single web app
- User-friendly interface built with Streamlit
- Pre-trained ML models for instant predictions
- Clean and preprocessed datasets

---

## 🛠️ Tech Stack

- **Language:** Python
- **Framework:** Streamlit
- **ML Library:** Scikit-learn
- **Notebooks:** Jupyter Notebook
- **Models:** Saved as `.sav` files using Pickle

---

## 📁 Project Structure

```
Medical-Diagnosis-Using-AI/
│
├── app.py                          # Main Streamlit web app
│
├── Datasets/
│   ├── diabetes_data.csv
│   ├── heart_disease_data.csv
│   ├── parkinson_data.csv
│   ├── hypothyroid.csv
│   ├── prepocessed_hypothyroid.csv
│   ├── prepocessed_lungs_data.csv
│   └── survey lung cancer.csv
│
├── Models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── Thyroid_model.sav
│   └── lungs_disease_model.sav
│
├── Diabetes_Prediction.ipynb
├── Heart_Disease_Prediction.ipynb
├── Parkinson's_Disease_Detection.ipynb
├── Thyroid.ipynb
└── Lung_Cancer.ipynb
```

---

## ⚙️ How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/SHIVASRIRAM2004/medical-diagnosis-using-ai.git
cd medical-diagnosis-using-ai
```

2. **Install dependencies**
```bash
pip install streamlit scikit-learn pandas numpy
```

3. **Run the app**
```bash
streamlit run app.py
```

---

## 📊 Model Training

Each disease has a dedicated Jupyter Notebook with:
- Data loading and exploration
- Preprocessing and feature selection
- Model training and evaluation
- Saving the trained model using Pickle

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@SHIVASRIRAM2004](https://github.com/SHIVASRIRAM2004)
- Email: shivaaa2004@gmail.com

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- Datasets sourced from public medical repositories
- Developed as a Minor Project for academic purposes
  
