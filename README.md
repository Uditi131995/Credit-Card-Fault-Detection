# Credit Card Fault Detection

# Dataset Details 

1. The dataset contains transactions made by credit cards in September 2013 by European cardholders.
2. Fraud Transaction : 492 transactions
3. Legit Transaction : 284,807 transactions
4. The dataset is highly imbalanced.
5. Features V1, V2, … V28 are the principal components obtained with PCA, due to privacy.
6. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


# To Balance the dataset 
Undersampling : 492 samples randomly taken from legit transaction and formed a join with the fraud transactions. 

# Model 
Logistic Regression : Used for Binary Classification 

# Training Accuracy 
 - 0.9402
 
# Testing Accuracy 
 - 0.9238

# Conclusion 
The model is not overfitted or underfitted as there is not much difference between the Accuracy Scores of train and test.
