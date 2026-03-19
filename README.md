# Breast Cancer Prediction System

A comprehensive machine learning solution for early cancer detection that predicts whether a breast tumor is benign or malignant using supervised classification algorithms.

## 📋 Overview

This project implements a complete data science workflow to build and evaluate predictive models for breast cancer diagnosis. By analyzing medical imaging features, the system helps identify malignant tumors with high accuracy, supporting early detection and treatment planning.

### Key Highlights

- 🎯 **Dataset:** Breast Cancer Wisconsin Diagnostic dataset (569 samples, 30 features)
- 🔬 **Features:** Real-world medical imaging measurements including radius, texture, perimeter, area, and smoothness
- 📊 **Workflow:** Complete ML pipeline from raw data to production-ready model
- 🏆 **Multiple Models:** Logistic Regression, SVM, Random Forest, and ensemble methods
- 📈 **Comprehensive Evaluation:** Accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices


## 📚 Detailed Workflow

### 1. **Data Loading & Exploration**
   - Load Wisconsin Diagnostic dataset
   - Display dataset shape, columns, and data types
   - Check for missing values and duplicates
   - Statistical summary of features

### 2. **Data Preprocessing**
   - Handle missing values and outliers
   - Encode target variable (benign/malignant)
   - Feature scaling and normalization
   - Address class imbalance if present

### 3. **Exploratory Data Analysis (EDA)**
   - Visualize feature distributions (histograms, box plots)
   - Correlation matrix heatmap
   - Feature importance analysis
   - Identify relationships between features and target variable

### 4. **Feature Engineering**
   - Select most relevant features
   - Handle multicollinearity
   - Dimensionality reduction (if applicable)
   - Create new features from existing ones

### 5. **Model Development**
   - **Logistic Regression:** Fast, interpretable baseline
   - **Support Vector Machine (SVM):** High-dimensional classification
   - **Random Forest:** Ensemble learning with feature importance
   - **Additional Models:** Gradient Boosting, K-Nearest Neighbors, etc.

### 6. **Model Evaluation**
   - Train-test split (80-20 or 70-30)
   - Cross-validation for robust assessment
   - Performance metrics:
     - ✓ Accuracy
     - ✓ Precision & Recall
     - ✓ F1-Score
     - ✓ Confusion Matrix
     - ✓ ROC-AUC Curve
   - Model comparison and selection

### 7. **Hyperparameter Tuning**
   - Grid Search / Random Search
   - Optimize best-performing model
   - Validate improvements

## 🔧 Prerequisites

- **Python:** 3.8 or later
- **Package Manager:** pip or conda
- **Jupyter:** For running the notebook

### Required Libraries
pandas>=1.3.0 numpy>=1.21.0 scikit-learn>=1.0.0 matplotlib>=3.4.0 seaborn>=0.11.0


### 🧠 Machine Learning Concepts
This project demonstrates:

- Supervised Learning: Classification with labeled data
- Data Preprocessing: Cleaning, scaling, encoding
- Model Selection: Comparing multiple algorithms
- Validation Techniques: Cross-validation, confusion matrices
- Performance Metrics: Beyond accuracy to precision, recall, F1-score
- Visualization: EDA for data understanding

---

## 👩‍💻 Author

**Ons Elfekih**  
IT Engineering Student — Business Intelligence  
🔗 [LinkedIn](https://www.linkedin.com/in/ons-elfekih) · [Portfolio](https://portfolio-elfekih-ons.vercel.app/)

---

## 📄 License

This project is for academic and portfolio purposes.
