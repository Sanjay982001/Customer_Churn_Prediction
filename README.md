# Customer Churn Prediction Project

Hello! This is my machine learning project for predict telecom customer churn. The main goal is to find out which customers will leave the company. This dataset has a challenge because the classes are imbalanced.

## What I do in this project
I generate synthetic telecom data for this project. The data has information like customer tenure, monthly charges, support calls, and contract type. 

First, I draw graphs to see how different things (like month-to-month contracts or high monthly charges) affect if a customer leaves. 

Then, I prepare the data. I use LabelEncoder for the text columns and do some feature engineering (like creating a support calls ratio and charges per product).

I use this machine learning model:
* Gradient Boosting Classifier (because it works very well for tabular data)

After I train the model, I print the ROC-AUC score and a classification report. I also draw a Confusion Matrix and a Feature Importances graph to show what drives the churn.

## Libraries I use
* numpy and pandas (for make and clean data)
* matplotlib and seaborn (for draw graphs)
* scikit-learn (for the machine learning model and math)

## How to use
Just download the `customer_churn.ipynb` file. Open it in Jupyter Notebook or JupyterLab and run the cells to see my code and graphs.
