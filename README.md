# 💳 Suspicious Transaction Identifier

This project aims to detect suspicious or fraudulent financial transactions using machine learning techniques. It involves cleaning the data, performing exploratory data analysis (EDA), training classification models, and evaluating their effectiveness in identifying potentially fraudulent activity.



## 🔍 Problem Statement

Financial fraud detection is a critical task for banking and fintech institutions. This project tackles the problem by building a supervised classification model that learns from historical transaction data to predict whether a transaction is suspicious or not.


## 🧪 Technologies Used

* Python 🐍
* Jupyter Notebook 📓
* Pandas & NumPy for data manipulation
* Matplotlib & Seaborn for visualization
* Scikit-learn for modeling and evaluation
* RandomForest
* Keras

  
## DataSet - Kaggle 


## 🛠️ Features

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Model Training (Logistic Regression, Decision Tree, Random Forest, etc.)
* Evaluation Metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC)


## 📈 Results

The models developed in this project were evaluated based on their ability to accurately distinguish between legitimate and fraudulent transactions. Given the significant class imbalance in the dataset (only ~0.17% of transactions are fraudulent), particular emphasis was placed on recall and F1 score, in addition to overall accuracy.

Model	Accuracy	Precision	Recall	F1 Score	AUC
Logistic Regression	High	High	Moderate	Moderate	Good
K-Nearest Neighbors	Moderate	Low-Med	High	Moderate	Fair
Support Vector Machine	High	High	Moderate	Moderate	Good
Decision Tree	Very High	High	High	High	Risk of Overfit
Random Forest	Excellent	High	High	High	Excellent
Neural Network	Excellent	Very High	Very High	Very High	Excellent



## 🧠 Future Improvements

* Real-time fraud detection integration
* Deployment using Flask or Streamlit
