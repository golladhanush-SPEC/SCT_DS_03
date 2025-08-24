# Bank Marketing Decision Tree Classifier

## Overview
This project implements a *Decision Tree classifier* to predict whether a customer will subscribe to a product or service based on *demographic and behavioral data* from the *Bank Marketing dataset* (UCI Machine Learning Repository).

The notebook includes:  
- Data loading and exploration  
- Preprocessing (One-Hot Encoding for categorical variables)  
- Splitting dataset into training and testing sets  
- Training a Decision Tree classifier  
- Model evaluation (accuracy, classification report, confusion matrix)  
- Decision Tree visualization  
- Conclusions and insights  

---

## Dataset
- Dataset: [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)  
- File: bank-full.csv  
- Target variable: y (whether the customer subscribed to a term deposit)

---

## How to Run
1. Clone or download this repository.  
2. Ensure bank-full.csv is in the same directory as the notebook.  
3. Open Bank_Marketing_DT.ipynb in *Jupyter Notebook* or *JupyterLab*.  
4. Run all cells to see outputs, evaluation metrics, and the decision tree visualization.

---

## Requirements
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- Jupyter Notebook

Install dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
