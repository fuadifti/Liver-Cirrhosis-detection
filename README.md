# Liver-cirosis-detection
A machine learning project that predicts liver cirrhosis stages using patient clinical data. The project includes data preprocessing, feature engineering, and a comparison of Decision Tree, Gradient Boosting, and K-Nearest Neighbors classifiers to identify the most accurate prediction model


# 🩺 Liver Cirrhosis Stage Classification

A Machine Learning project that predicts the stage of liver cirrhosis using patient clinical information. The project compares multiple classification algorithms and identifies the most accurate model for predicting disease stages.

## 📌 Project Overview

Liver cirrhosis is a chronic liver disease that progresses through multiple stages. Early prediction of the disease stage can assist healthcare professionals in making timely clinical decisions.

This project applies machine learning techniques to classify liver cirrhosis into three stages using demographic, medical, and laboratory features.

The project was developed as part of the **CSE422 – Artificial Intelligence** Lab Project. :contentReference[oaicite:0]{index=0}

---

## 📂 Repository Structure

```
├── Group_06_Sec_03_CSE422_Lab_project.ipynb   # Complete implementation
├── ML_Project.pdf                             # Project report
├── README.md                                  # Project documentation
```

---

## 📊 Dataset

- **Dataset:** Liver Cirrhosis Stage Classification
- **Source:** Kaggle
- **Classification Type:** Multi-class Classification
- **Target Variable:** Stage (1, 2, 3)
- **Total Samples:** 25,000
- **Features:** 19 (Numerical + Categorical) :contentReference[oaicite:1]{index=1}

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Duplicate value removal
- Label Encoding
- One-Hot Encoding
- Feature Engineering
- Min-Max Feature Scaling
- Train-Test Splitting

Categorical features were transformed into numerical representations before model training. :contentReference[oaicite:2]{index=2}

---

## 🤖 Machine Learning Models

Three classification algorithms were trained and evaluated:

- Decision Tree Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN) Classifier :contentReference[oaicite:3]{index=3}

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Gradient Boosting Classifier | **79%** |
| Decision Tree Classifier | 74% |
| K-Nearest Neighbors | 71% |

Gradient Boosting achieved the highest overall classification accuracy. :contentReference[oaicite:4]{index=4}

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Navigate into the project

```bash
cd your-repository
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📖 Project Report

A detailed report describing the dataset, preprocessing, feature engineering, model training, evaluation, and comparison is available in **ML_Project.pdf**.

---

## 👥 Authors

- **Moutasim Fuad Ifti**
- **Mohd Tashwaruddin Safin** :contentReference[oaicite:5]{index=5}

---

## 📜 License

This repository is intended for educational and academic purposes.
