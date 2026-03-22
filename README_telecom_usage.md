# 📡 Telecom Usage Analysis & Customer Segmentation

End-to-end telecom data analysis project covering EDA, churn classification with 9 ML models, and unsupervised customer segmentation using K-Means clustering — helping telecom businesses understand usage patterns and target the right customers.

---

## 👩‍💻 Author

| | |
|---|---|
| **Name** | Anushree R |
| **Email** | anushreerpoojary2611@gmail.com |
| **GitHub** | [github.com/AnushreeRPoojary](https://github.com/AnushreeRPoojary) |

---

## 📌 Problem Statement

Telecom companies deal with massive volumes of customer usage data. This project aims to:
- Analyse customer usage patterns (data, charges, tenure)
- Predict customer churn using classification models
- Segment customers into meaningful groups using clustering
- Provide business insights for targeted marketing

---

## 📂 Dataset

- 📁 File: `telecom_usage_data.csv`
- 📊 Features: `age`, `tenure_months`, `monthly_charges`, `total_charges`, `data_usage_gb`, `gender`, `contract_type`, `payment_method`, `internet_service`
- 🎯 Target: Churn (binary classification)

---

## 🔬 Project Workflow

```
📥 Load Data
    ↓
🔍 Exploratory Data Analysis (EDA)
    ↓
📊 Distribution & Outlier Analysis
    ↓
🔗 Correlation Analysis
    ↓
🛠️ Feature Engineering
    ↓
⚖️ Handle Class Imbalance (SMOTE)
    ↓
🤖 Train 9 ML Models (Classification)
    ↓
📊 Compare & Evaluate Models
    ↓
🔵 K-Means Customer Segmentation
    ↓
📉 PCA Visualization
    ↓
💡 Segment Profiling & Insights
```

---

## 📊 Models Used

### Classification (Churn Prediction)
| Model | Type |
|---|---|
| Logistic Regression | Linear |
| Decision Tree | Tree-based |
| Random Forest | Ensemble |
| Extra Trees | Ensemble |
| Gradient Boosting | Boosting |
| AdaBoost | Boosting |
| XGBoost | Boosting |
| KNN | Instance-based |
| SVM | Kernel-based |

### Clustering (Customer Segmentation)
| Model | Type |
|---|---|
| K-Means | Unsupervised |
| PCA | Dimensionality Reduction |

---

## 📈 Key Visualizations

| Plot | Description |
|---|---|
| Distribution plots | Age, tenure, charges, data usage |
| Category bar charts | Gender, contract, payment, internet service |
| Box plots | Outlier detection per feature |
| Correlation heatmap | Feature relationships |
| Scatter plots | Data usage vs charges, tenure vs total charges |
| SMOTE balance chart | Before vs after class balancing |
| Model comparison bar | Accuracy, Precision, Recall, F1, AUC-ROC |
| Confusion matrices | All 9 models |
| ROC curves | All models on one chart |
| Feature importance | Top features from Random Forest |
| Elbow curve | Optimal K for clustering |
| PCA scatter | Customer segments in 2D |
| Segment profiles | Box plots per segment |
| Segment distribution | Customer count per segment |

---

## 👥 Customer Segments

| Segment | Label |
|---|---|
| 0 | Low Usage / Short Tenure |
| 1 | Heavy Data Users |
| 2 | Long Tenure / Loyal Customers |
| 3 | High Value / Premium Customers |

---

## 🗂️ Project Structure

```
telecom-usage-analysis/
├── telecom_usage_analysis.ipynb     ← main notebook
├── telecom_usage_data.csv           ← dataset
├── *.png /outputs                           ← saved visualizations
└── README.md
```

---

## ⚙️ Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

---

## 🚀 How to Run

### Jupyter Notebook
```bash
jupyter notebook telecom_usage_analysis.ipynb
```

### VS Code
1. Open `telecom_usage_analysis.ipynb`
2. Place CSV in same folder
3. Click **Run All** ▶▶

### Google Colab
1. Upload `telecom_usage_data.csv` using:
```python
from google.colab import files
uploaded = files.upload()
```
2. Run all cells ✅

---

## 💡 Key Findings

- **Heavy data users** tend to have higher monthly charges
- **Long tenure customers** are less likely to churn
- **Contract type** is the strongest predictor of churn
- **4 distinct customer segments** identified via K-Means
- **Random Forest / XGBoost** consistently best performing models

---

## 📤 Output

- Full model comparison table (Accuracy, Precision, Recall, F1, AUC-ROC)
- Best model selected automatically
- Customer segment labels added to dataset
- PCA visualization of all segments

---

## 📄 License

MIT License — free to use and modify.



*Built by Anushree R — AI & ML Engineer*  
*B.E. Artificial Intelligence & Machine Learning, SMVITM Udupi*
