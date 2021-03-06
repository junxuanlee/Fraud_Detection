# Fraud_Detection

This project is an implementation of Gaussian Naive Bayes Classifier to detect fraudulent bank transactions based on a financial dataset at: https://www.kaggle.com/ealaxi/paysim1

The following are the processes implemented on the dataset:
### Data Visualization
    i) Kernel Density Estimate (KDE) Plot
    ii) Box Plot
    iii) Scatter Plot
    iv) Pair Plot
    
### Feature Engineering
    i) Added 'limit', 'frequent', 'merchant' columns
    
### Preprocessing 
    i) Improved variable skewness through log-transform
    ii) Removed variables with high correlations
    iii) Standardization
    iv) One-hot encoding
    v) Improved imbalanced target distribution through Synthetic Minority Oversampling Technique (SMOTE)

### Model building
    i) Logistic Regression
    ii) Decision Tree
    iii) Random Forest
    iv) Gaussian Naive Bayes
    
At the end of the implementations, it was decided that Gaussian Naive Bayes Classifier is preferred because it gives no false negatives compared to other classifiers. This is important in fraud detection because a single false negative in the detection can cause huge loss to the bank where any number of false positives will not impact the bank.
    
