# Default-Credit-Card-Payment-Project
Predict the default behavior of credit card customers and analyze the UCI default data set of credit card customers, which contains information such as defaults, demographics, credit data, payment history, and billing statements of credit card customers in Taiwan from April 2005 to September 2005.
The analysis is divided into different steps:

- Data exploration: describe attributes and understand each feature (structure, size, dimensions and the relationship between the different features).
- Data cleaning: data processing, including error correction, outlier detection, correlation analysis, feature selection (using SelectKBest).
- Outlier detection: Identify and delete rows that are considered possible outliers through various outlier detection algorithms(using Q-Q plot,Boxplot,Isolation forests algorithm and Local Outlier Factor).
- Correlation and dimensionality reduction: analysis of correlated features and application of PCA.
- Class imbalance management: apply some techniques to manage class imbalance(using k-means SMOTE, Cluster Centroids).
- Classification algorithms for modelization and metrics for evaluation.
