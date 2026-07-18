# ❤️ Heart Disease Prediction using Machine Learning

This project performs **Exploratory Data Analysis (EDA)**, **data preprocessing**, **feature engineering**, and **machine learning model training** to predict whether a patient is likely to have heart disease based on medical attributes.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. This notebook analyzes the Heart Disease dataset, cleans the data, visualizes important patterns, and trains multiple machine learning models to identify the best-performing classifier.

---

## 📂 Dataset

**Dataset:** `heart.csv`

The dataset contains patient health information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope
- Heart Disease (Target)

---

## 🚀 Features

- Data Exploration (EDA)
- Data Cleaning
- Missing/Invalid Value Handling
- Feature Encoding
- Feature Scaling
- Data Visualization
- Model Training
- Model Comparison
- Model Serialization

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset Information
- Statistical Summary
- Duplicate Detection
- Missing Value Analysis
- Distribution Plots
- Count Plots
- Box Plots
- Violin Plots
- Correlation Heatmap

---

## 🧹 Data Preprocessing

The following preprocessing steps are performed:

- Removal of duplicate records
- Replacement of invalid Cholesterol values (0) with mean value
- Replacement of invalid Resting Blood Pressure values (0) with mean value
- One-Hot Encoding of categorical variables
- Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models

The following algorithms are trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

Evaluation Metrics:

- Accuracy Score
- F1 Score

---

## 📦 Libraries Used

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

---

## 📁 Project Structure

```
Heart Disease Prediction/
│
├── Heart.ipynb
├── heart.csv
├── Logistic_heart.pkl
├── scaler.pkl
├── Columns.pkl
└── README.md
```

---

## 💾 Saved Files

After training, the notebook saves:

- `Logistic_heart.pkl` → Trained Logistic Regression model
- `scaler.pkl` → StandardScaler object
- `Columns.pkl` → Feature column names

These files can be used directly while deploying the model using Flask, Streamlit, or FastAPI.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
```

### 2. Navigate to the project

```bash
cd heart-disease-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib sheryanalysis
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Heart.ipynb** and run all cells.

---

## 📈 Workflow

```
Dataset
   │
   ▼
EDA
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Save Best Model
```

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Selection
- Ensemble Learning
- XGBoost / LightGBM
- Model Deployment using Streamlit
- Docker Containerization

---

## 👨‍💻 Author

<<<<<<< HEAD
**Saket Das**
=======
**Saket Das**
>>>>>>> 5731b3f232a45f987d4f6d0640a30e0b308df1e4
