# 🔍 Fraud Detection System

This project focuses on the **proactive detection of fraudulent transactions** using machine learning and advanced data analysis techniques.

---

## 📚 Dataset
- **Features**: Transaction amount, origin and destination account balances, transaction type, etc.
- **Target**: `isFraud`
- **Note**:  
  The original dataset (`Fraud.csv`) exceeds 100MB and cannot be uploaded directly to GitHub.  
  ➔ You can download a similar dataset from [Kaggle](https://www.kaggle.com/) or generate a simulated dataset for testing.

---

## 🛠️ Workflow
1. **Data Cleaning**
   - Handling missing values
   - Removing outliers
2. **Feature Engineering**
   - Encoding categorical variables
   - Correlation analysis
   - Variance Inflation Factor (VIF) calculation for multicollinearity
3. **Model Building**
   - Random Forest Classifier
   - Handling class imbalance
4. **Model Evaluation**
   - Metrics: Precision, Recall, F1-Score, ROC-AUC
5. **Model Saving**
   - Trained model saved as `fraud_model.pkl` for easy deployment

---

## 🚀 How to Run Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Fraud-Detection-Project.git
    cd Fraud-Detection-Project
    ```

2. Create a virtual environment (recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch the Jupyter Notebook:
    ```bash
    jupyter notebook Fraud_Detection_Nishnat.ipynb
    ```

---

## 📦 Requirements

> Here’s your example `requirements.txt` contents:

```text
pandas>=1.5.3
numpy>=1.24.2
scikit-learn>=1.2.2
matplotlib>=3.7.1
seaborn>=0.12.2
statsmodels>=0.13.5
jupyter>=1.0.0
```

✅ Common, stable versions to avoid compatibility issues!

---

## 📁 Project Structure
```
Fraud-Detection-Project/
│
├── Fraud_Detection_Nishnat.ipynb   # Main Jupyter Notebook
├── fraud_model.pkl                 # Saved machine learning model
├── requirements.txt                # List of dependencies
├── README.md                       # Project documentation
└── data/                           # Folder for dataset (not uploaded)
```

---

## 🤝 Contribution Guidelines

If you wish to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit:
    ```bash
    git commit -m "Add: New feature or bug fix"
    ```
4. Push to your branch:
    ```bash
    git push origin feature-name
    ```
5. Create a Pull Request.

---

## 📢 Notes
- Consider using platforms like Google Colab or Kaggle for heavy dataset processing.
- Potential future improvements:
  - Hyperparameter tuning (GridSearchCV)
  - Ensemble methods (XGBoost, LightGBM)
  - Real-time fraud detection with streaming data

---

## 👨‍💻 Author
**Nishnat Dangoria**  
_Always learning, always building!_
