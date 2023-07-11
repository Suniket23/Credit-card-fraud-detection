# Credit-card-fraud-detection
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not.
# Algorithms Used
The Local Outlier Factor (LOF):Algorithm used for outlier detection in data mining and machine learning. It is a non-parametric method that identifies data points that deviate significantly from their local neighborhood.
Support Vector Machines (SVM):Supervised machine learning algorithm used for classification and regression tasks. It is a powerful and versatile algorithm that can handle linear and non-linear data separations by constructing decision boundaries or hyperplanes in high-dimensional spaces.
The Isolation Forest algorithm:Unsupervised machine learning algorithm used for outlier detection. It is based on the concept of isolating anomalies or outliers in a dataset by constructing random decision trees.

# Dataset
the dataset is taken from kaggle.The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Results and Conclusion
This project implements the machine learning algorithms like SVM, LOF and Isolation forest algorithm.we compair the accuracy of these algorithms and we reached to conclusion that isolation forest and local outlier factor algorithms have high accuracy about 99% and works better than the support vector machine.
