# Default-Credit-Card-Payment-Project
Predict the default behavior of credit card customers and analyze the UCI default data set of credit card customers, which contains information such as defaults, demographics, credit data, payment history, and billing statements of credit card customers in Taiwan from April 2005 to September 2005.
The analysis is divided into different steps:

- Data exploration: describe attributes and understand each feature;
- Data cleaning: data processing, including error correction, outlier detection, correlation analysis, feature selection (using SelectKBest);
- Outlier detection: Identify and delete rows that are considered possible outliers through various outlier detection algorithms(using k-means SMOTE, Cluster Centroids);
- Correlation and dimensionality reduction: analysis of correlated features and application of PCA;
- Class imbalance management: apply some techniques to manage class imbalance;
- Classification algorithms and metrics for evaluation;
