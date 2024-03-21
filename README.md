# Fraudulent-ATM-transaction-Detection
*Capstone project* -
Banking Domain Anomaly Detection Project
Problem Statement

The Australian banking client of PredCatch Analytics is facing profitability and reputation issues 
due to fraudulent ATM transactions. PredCatch aims to mitigate these issues by developing a predictive 
model to detect and prevent fraudulent transactions in real-time. As a Data Scientist at PredCatch, 
your task is to build this fraud detection and prevention predictive model using the provided data.
Data Description

The data contains transaction information, including masked variables and features such as location (geo_scores), 
proprietary index (Lambda_wts), network turn around times (Qset_tats), and vulnerability qualification score (instance_scores). 
The target variable to predict is 'Target', indicating fraudulent or non-fraudulent transactions.
Approach

Given the imbalanced nature of the data, various machine learning algorithms were utilized for anomaly detection and classification. 
The models employed include Logistic Regression, Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier,
Support Vector Machine, K Nearest Neighbor, Naive Bayes Theorem, Voting Classifier, Stacking Method, and Anomaly Detection
using Isolation Forest Classifier.

Implementation

    Data Preprocessing: Handled masked variables and missing values, and performed feature engineering.
    Model Training: Trained multiple classifiers using different algorithms.
    Model Evaluation: Evaluated models using performance metrics such as accuracy, precision, recall, and F1-score.
    Anomaly Detection: Utilized Isolation Forest, Local Outlier Factor, and One-Class SVM for anomaly detection.
    Final Model: Constructed a final classification model using an ensemble approach combining Isolation Forest, 
    Local Outlier Factor, and One-Class SVM.

Usage

    Clone the repository to your local machine.
    Install the required dependencies specified in the requirements.txt file.
    Run the preprocessing scripts to clean and prepare the dataset.
    Experiment with different machine learning models and anomaly detection techniques using provided scripts.
    Evaluate model performance and fine-tune parameters as necessary.
    Utilize the final classification model for fraud detection and prevention.

Conclusion

The project successfully addresses the challenge of fraud detection in the banking domain by implementing various machine learning algorithms and anomaly detection techniques. The final classification model offers a robust solution to identify and prevent fraudulent transactions, thereby safeguarding the client's profitability and reputation. Further enhancements and optimizations can be explored to improve model performance in real-world scenarios.
