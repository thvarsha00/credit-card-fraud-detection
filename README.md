
   #  Credit Card Fraud Detection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thvarsha00/credit-card-fraud-detection/blob/main/credit-card-fraud-detection.ipynb)

##  Project Overview
This project explores **credit card fraud detection** using machine learning techniques and exploratory data analysis (EDA). The dataset is highly imbalanced, with fraudulent transactions making up less than 1% of all transactions, which makes the problem both challenging and realistic.

The notebook includes:
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) with **Matplotlib, Seaborn, Plotly**  
- Visualizations of fraud vs. non-fraud transaction patterns  
- Feature scaling and **dimensionality reduction with PCA**  
- Model training & evaluation for fraud detection  

---

##  Dataset
The dataset used is the **Credit Card Fraud Detection dataset** from Kaggle.  
It contains anonymized transaction features (V1, V2, … V28), the transaction `Amount`, and the target variable `Class`:  

- `0` → Non-fraud  
- `1` → Fraud  

🔗 [Dataset on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

##  Visualizations
Some key visualizations included in the notebook:
- Distribution of fraudulent vs. non-fraudulent transactions  
- Correlation heatmap of features  
- PCA projection of high-dimensional features  
- Transaction amount distributions  
- Time vs. transaction analysis  

---

## ⚙ Tech Stack
- Python   
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  

---

## How to Run
### Option 1: Open in Google Colab
Click the Colab badge above  and run the notebook directly in your browser.  

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/thvarsha00/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
