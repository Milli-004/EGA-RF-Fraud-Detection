# 💳 Enhanced Genetic Algorithm–Optimized Random Forest (EGA-RF) for Credit Card Fraud Detection

## 🧠 Overview
This project implements an **Enhanced Genetic Algorithm–Optimized Random Forest (EGA-RF)** model for detecting fraudulent credit-card transactions.
It combines **Genetic Algorithm (GA)** for intelligent feature selection with a **Random Forest Classifier** for accurate classification.

## 🎯 Objectives
- Improve fraud detection accuracy using optimized features.
- Handle class imbalance using **SMOTE + Tomek Links**.
- Compare performance with baseline ML models (Logistic Regression, SVM, Random Forest).
- Provide interpretable results through feature-importance visualization.

## 🗂️ Dataset
- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Records: 284,807 transactions
- Fraud Cases: 492 (0.172%)
- Features: 30 (V1–V28, Time, Amount) + Target `Class`

## ⚙️ Tech Stack
- **Language:** Python 3.10
- **Libraries:** pandas, numpy, scikit-learn, imblearn, deap, matplotlib, seaborn
- **Environment:** Jupyter Notebook / VS Code

## 🔬 Implementation Steps
1. **Data Preprocessing** – Scaling & Balancing (SMOTE + Tomek Links)
2. **Feature Selection** – Genetic Algorithm (DEAP)
3. **Model Training** – Random Forest Classifier
4. **Evaluation** – Accuracy, F1, ROC-AUC
5. **Visualization** – Confusion Matrix, ROC Curve, Feature Importance
6. **Comparison** – Baseline Models (LR, SVM, RF) vs Proposed (EGA-RF)

## 📈 Visualizations
- Confusion Matrix Heatmap  
- ROC Curve  
- Feature Importance Plot  


## 🏁 Conclusion
The **EGA-RF model** achieved the highest performance among baseline models, proving that **GA-based feature selection** significantly enhances Random Forest accuracy and recall.  
This approach is scalable for real-time fraud-detection systems in banking and fintech.

## ✨ Author
**Milli Srivastava**  
B.Tech CSE (3rd Year), Invertis University, Bareilly
