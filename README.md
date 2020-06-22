## Predict-Employee-Churn-with-Decision-Trees-and-Random-Forests-using-Scikit-Learn-in-Python

To identify whether employees are likely to quit (which employees in particular) using Decision tree model.

Steps:

####### 1. Import the relevant libraries

####### 2. Load the data—pd.read_csv(“ ”) and import pandas_profiling summary using df.profile_report() function.

####### 3. One hot encoding to handle categorical variables (we have 2 categorical variables in our dataset- “department” and “salary”)-- we ned to transform these categorical variable in an acceptable format. Pandas provide an easy function to perform the same which is “pd.get_dummies” 

####### 4. Look for the class Imbalance- used yellowbrick library for the same

####### 5. Splitting the dataset into Train & Test

####### 6. Build a decision tree and a random forest classifier

####### 7. Feature Importance & Evaluation Metrics using ROC curve

