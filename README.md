# Predicting Anxiety Levels with Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Project Overview
This is a **Mini Project** for the Machine Learning course. The goal is to build classification models to predict anxiety levels (binary: High/Low) based on various lifestyle and health features.

**Models Implemented:**
- Logistic Regression (from scratch and using scikit-learn)
- Gaussian Naive Bayes

## 📁 Project Structure
anxiety-prediction-ml/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── main.ipynb
├── data/
│   └── enhanced_anxiety_dataset.csv
├── reports/
│   └── report.pdf
└── models/ (optional)


## 🚀 How to Run
```bash
git clone https://github.com/omid-talebi/anxiety-prediction-ml.git
cd anxiety-prediction-ml

pip install -r requirements.txt


## 📊 Results
| Model                | Accuracy | Precision | Recall | F1-Score | AUC-ROC |
|----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | **84.21%** | 79.60%  | 67.87% | 73.27%  | **0.913** |
| Naive Bayes          | 81.03%   | 75.60%  | 59.79% | 66.77%  | 0.885   |



**Best Model**: Logistic Regression performs better overall.

## 📄 Full Report
The complete project report (in Persian) is available in:  
[**reports/report.pdf**](reports/report.pdf)

## 🛠 Technologies
- **Data Handling**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn, PCA
- **Environment**: Jupyter Notebook

## 📜 License
MIT License — see the [LICENSE](LICENSE) file for details.
