# Predict-Employee-Churn-with-Decision-Trees-and-Random-Forests-using-Scikit-Learn-in-Python

To identify whether employees are likely to quit (which employees in particular) using Decision tree model.

Steps:

Import the relevant libraries

Load the data—pd.read_csv(“ ”) and import pandas_profiling summary using df.profile_report() function.

One hot encoding to handle categorical variables (we have 2 categorical variables in our dataset- “department” and “salary”)-- we ned to transform these categorical variable in an acceptable format. Pandas provide an easy function to perform the same which is “pd.get_dummies” 

Look for the class Imbalance- used yellowbrick library for the same

Splitting the dataset into Train & Test

Build a decision tree and a random forest classifier

Feature Importance & Evaluation Metrics using ROC curve

