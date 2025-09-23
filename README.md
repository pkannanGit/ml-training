#Credit risk predictor ML project/.

This project explores supervised machine learning techniques to predict credit risk based on a 40 features such as client income, employment, social circle, etc...

---

##  Project Overview
- Preprocesses raw client income and credit datasets
- Data cleaning - Handles missing/invalid values for easy parsing
- Exploratory data analysis to gain intuition regarding which features influence defaults
- Uses logistic regression baseline model (ROC score of 0.726)
- Introduce decision tree to capture further complexity
- Trains and evaluates an **XGBoost Classifier** and random forest for improved accuracy (ROC 0.773)
- Evaluates models using metrics such as ROC-AUC, TPR, FPR, precision, and recall

---

## 📂 Repository Structure

college_mlprj/
├── Data_Dictionary.csv

├── Train_Dataset.csv

├── training.ipynb # main Jupyter notebook with all code

└── README.md

Future Work:

Feature engineering (e.g., income-to-loan ratio)

Deploy model as a web API using Flask or FastAPI
