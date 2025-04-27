🔍 Fraud Detection System
This project focuses on the proactive detection of fraudulent transactions using machine learning and advanced data analysis techniques.

📚 Dataset
Features: Transaction amount, origin and destination account balances, transaction type, etc.

Target: isFraud

Note:
The original dataset (Fraud.csv) exceeds 100MB and cannot be uploaded directly to GitHub.
➔ You can download a similar dataset from Kaggle or generate a simulated dataset for testing.

🛠️ Workflow
Data Cleaning

Handling missing values

Removing outliers

Feature Engineering

Encoding categorical variables

Correlation analysis

Variance Inflation Factor (VIF) calculation for multicollinearity

Model Building

Random Forest Classifier

Handling class imbalance

Model Evaluation

Metrics: Precision, Recall, F1-Score, ROC-AUC

Model Saving

Trained model saved as fraud_model.pkl for easy deployment

🚀 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Fraud-Detection-Project.git
cd Fraud-Detection-Project
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Fraud_Detection_Nishnat.ipynb
📦 Requirements
Python 3.10+

pandas

numpy

scikit-learn

matplotlib

seaborn

statsmodels

📁 Project Structure
bash
Copy
Edit
Fraud-Detection-Project/
│
├── Fraud_Detection_Nishnat.ipynb   # Main Jupyter Notebook
├── fraud_model.pkl                 # Saved machine learning model
├── requirements.txt                # List of dependencies
├── README.md                       # Project documentation
└── data/                           # Folder for dataset (not uploaded)
📢 Notes
For large datasets, consider working with cloud platforms like Google Colab or Kaggle Notebooks.

Further improvements can include:

Hyperparameter tuning

Ensemble methods

Real-time fraud detection pipelines

👨‍💻 Author
Nishnat Dangoria
