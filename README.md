# ❤️ Heart Disease Analysis & Prediction

A data analysis and machine learning project that examines clinical patient data to identify key risk factors for heart disease — and builds and compares classification models to determine the most effective method for predicting whether a patient is at high or low risk.

---

## 📁 Project Structure

```
heart-disease-analysis/
│
├── heart-disease-analysis-prediction.ipynb   # Main notebook: EDA, visualizations & classification models
└── heart.csv                                 # Dataset: 1,025 patient records with clinical features
```

---

## 📊 Dataset

The dataset contains **1,025 patient records** with 13 clinical features and a binary target variable. Based on the well-known [Heart Disease Dataset from the UCI Machine Learning Repository](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

| Column | Description |
|--------|-------------|
| `age` | Age of the patient (years) |
| `sex` | Sex (1 = male, 0 = female) |
| `cp` | Chest pain type (0–3) |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg` | Resting electrocardiographic results (0–2) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = yes, 0 = no) |
| `oldpeak` | ST depression induced by exercise relative to rest |
| `slope` | Slope of the peak exercise ST segment (0–2) |
| `ca` | Number of major vessels coloured by fluoroscopy (0–3) |
| `thal` | Thalassemia type (0 = normal, 1 = fixed defect, 2 = reversible defect) |
| `target` | Heart disease diagnosis — **target variable** (1 = disease, 0 = no disease) |

---

## 🔍 Project Overview

### Exploratory Data Analysis (EDA)
- Distribution of patients with and without heart disease
- Analysis of risk factors: age, sex, chest pain type, and cholesterol levels
- Correlation heatmap to identify relationships between clinical features
- Feature-by-feature breakdowns against the target variable using visualizations

### Classification Models
- Multiple classification models trained to predict the presence of heart disease
- Model comparison to determine the most effective classifier for this dataset
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrices

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation

```bash
git clone https://github.com/yungxuan819/heart-disease-analysis.git
cd heart-disease-analysis
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run

```bash
jupyter notebook heart-disease-analysis-prediction.ipynb
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| matplotlib / seaborn | Data visualizations |
| scikit-learn | Classification models & evaluation |
| Jupyter Notebook | Development environment |
