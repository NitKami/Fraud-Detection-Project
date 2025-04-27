# 🔍 Fraud Detection Project

This project involves proactive detection of fraudulent transactions using machine learning and data analysis techniques.

## 📚 Dataset
- Features like transaction amount, original and destination account balances, transaction type, etc.
- Target variable: `isFraud`
The original dataset (Fraud.csv) is too large for GitHub upload (>100MB).  
You can download similar fraud detection datasets from Kaggle or create your own simulated dataset for testing.

## 🛠 Project Steps
- Data Cleaning (missing values, outliers)
- Feature Engineering (encoding, correlation analysis, VIF calculation)
- Model Building (Random Forest Classifier with class balancing)
- Model Evaluation (Precision, Recall, F1-Score, ROC-AUC)
- Model Saving (`fraud_model.pkl`)

## 🚀 How to Run Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Fraud-Detection-Project.git
    cd Fraud-Detection-Project
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Notebook:
    ```bash
    jupyter notebook Fraud_Detection_Nishnat.ipynb
    ```

## 📦 Requirements
- Python 3.10+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- statsmodels

## 🎯 Project Structure