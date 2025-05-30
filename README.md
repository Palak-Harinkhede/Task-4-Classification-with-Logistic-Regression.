# 🎯 Breast Cancer Classification - Logistic Regression (AIML Internship Task 4)

## 📌 Task Objective
Build a **binary classifier** using **Logistic Regression** to detect breast cancer based on diagnostic features.

---

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📂 Dataset
- File: `data.csv`
- Source: [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Description: The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The target column is `diagnosis`, where:
  - `M` = Malignant
  - `B` = Benign

---

## 🧠 Workflow

### 1. Data Loading & Cleaning
- Loaded dataset using `pandas`
- Dropped irrelevant columns like `id` and `Unnamed: 32`

### 2. Preprocessing
- Mapped diagnosis to binary: `M = 1`, `B = 0`
- Standardized feature values using `StandardScaler`

### 3. Model Training
- Split data using `train_test_split`
- Trained `LogisticRegression` model on training data

### 4. Evaluation
- Evaluated performance using:
  - Confusion Matrix
  - Classification Report
  - ROC-AUC Score
  - ROC Curve

---

## 📊 Results

### ✅ Classification Report
| Metric        | Value (Sample) |
|---------------|----------------|
| Precision     | 0.96           |
| Recall        | 0.98           |
| F1-Score      | 0.97           |
| Accuracy      | 0.97           |
| ROC-AUC Score | 0.99           |

*(Note: Actual values may vary slightly depending on the train-test split)*

---

## 📈 Visuals

- 🔵 **Confusion Matrix**
- 📉 **ROC Curve**
- 🌀 **Sigmoid Function Plot**

All plots are included in the notebook for interpretation.

---

## 📁 Repository Contents

- `data.csv` – Breast cancer dataset
- `Task4(1).ipynb` – Jupyter Notebook with full code
- `README.md` – This summary file

---

## 🔍 Interview Prep (What I Learned)
- Difference between logistic and linear regression
- How sigmoid maps output to [0,1] range
- Use of precision vs recall
- ROC-AUC and its interpretation
- Threshold tuning and effect on classification
- Importance of handling class imbalance

---


