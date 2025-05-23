# 🔐 Intrusion Detection Using Supervised Machine Learning  
**Firewall Log Analysis from a Nepalese ISP**

This repository contains the implementation of a supervised machine learning pipeline designed to detect network intrusions using labeled firewall logs. The project uses real-world data from a Nepalese ISP and applies classical ML models to classify traffic as either normal or malicious.

---

## 📁 Project Structure

```
├── data/                   # Cleaned and processed datasets
├── plots/                  # ROC curves, confusion matrices, heatmaps
├── notebooks/              # Jupyter notebooks for analysis and modeling
├── results/                # Evaluation metrics, cross-validation scores
└── README.md               # Project documentation
```

---

## 📊 Project Objective

To design and evaluate supervised ML models capable of detecting intrusions in structured firewall log data. The project emphasizes:

- Data preprocessing and feature engineering
- Statistical feature selection (`SelectKBest`)
- Training: Random Forest, Logistic Regression, SVM
- Evaluation using ROC, AUC, F1-Score, and Confusion Matrix
- Agile pipeline structure for repeatable and modular analysis

---

## 🧪 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score | AUC   |
|---------------------|----------|-----------|--------|----------|--------|
| Random Forest       | 0.88     | 0.900     | 0.852  | 0.875    | 0.934 |
| Logistic Regression | 0.73     | 0.732     | 0.717  | 0.724    | 0.794 |
| SVM                 | 0.885    | 0.910     | 0.852  | 0.880    | 0.931 |

---

## 🛠️ Tools & Libraries

- Python 3.x
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/kshetris/NID_Final-Thesis.git
   cd intrusion-detection-ml
   ```

2. Open the notebook:
   ```bash
   jupyter notebook
   ```

3. Execute cells in order:
   - Data Preprocessing
   - Feature Selection
   - Model Training
   - Evaluation and Plot Generation

---

## 📌 Dataset Information

- Data sourced from firewall logs provided by a Nepalese ISP
- 10,000 labeled samples: 5,000 normal, 5,000 attack
- Used for binary classification: normal (0) vs. attack (1)
- Includes both numerical and encoded categorical features

---

## ⚠️ Disclaimer

This project is for academic and research purposes only.  
Results may not generalize to production or high-security environments without further testing.

---

