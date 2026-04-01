CREDIT CARD FRAUD DETECTION

This dataset contains real credit card transactions made by European cardholders in September 2013. It is widely used in machine learning for fraud detection problems in finance.

Total transactions: 100,000
Fraud rate: ~0.17% (very rare)
This makes it a highly imbalanced dataset, which is very realistic in finance.

The dataset includes several types of features. The Time variable records the number of seconds elapsed between each transaction and the first transaction in the dataset, while the Amount variable represents the monetary value of the transaction. The remaining features, labeled V1 through V28, are numerical variables that have been transformed using Principal Component Analysis (PCA). This transformation was applied to anonymize sensitive information, meaning these features do not have direct real-world interpretations but still capture important underlying patterns in the data. The target variable, Class, indicates whether a transaction is legitimate (0) or fraudulent (1). 

This dataset is widely used in the field of finance because it addresses a critical problem faced by banks and payment systems: detecting fraudulent transactions. Financial institutions use similar data to develop machine learning models that can identify suspicious behavior in real time, helping to prevent financial losses and improve security. It is also useful for studying risk management, anomaly detection, and binary classification techniques
