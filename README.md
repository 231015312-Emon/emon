Approach-
The goal of this project is to develop a machine learning model that predicts whether a customer will subscribe to a term deposit based on their demographic and banking-related information.
This problem is formulated as a binary classification task, where the target variable has two possible outcomes:
Yes (1) → Customer subscribes
No (0) → Customer does not subscribe
A Logistic Regression model is used because it is:

Simple and efficient
Interpretable (important in banking decisions)
Well-suited for binary classification problems
The model learns the relationship between customer features and the probability of subscription.
Methodology-
The dataset used is the Bank Marketing Dataset, which contains information collected from previous marketing campaigns.
Key details:
17 input features (customer and campaign information)
1 target variable (y: yes/no)
Data includes:
Demographics (age, job, marital status, education)
Financial details (balance, loans)
Campaign-related features (contact type, duration, previous outcomes)
Features are divided into:
Numerical features → scaled using StandardScaler
Categorical features → encoded using One-Hot Encoding
A ColumnTransformer is used to apply preprocessing steps efficiently.
The dataset is split into:
Training set (80%)
Testing set (20%)
Stratified sampling is used to preserve class distribution.
A Pipeline is used to combine preprocessing and model training into a single workflow:

Step 1: Data preprocessing
Step 2: Logistic Regression model
Findings-
The Logistic Regression model successfully predicts whether a customer is likely to subscribe to a term deposit
It provides probability-based outputs, which are useful for decision-making in marketing strategies
The model performs well when:
Data is properly preprocessed
Features are scaled and encoded correctly
Observations:
Some imbalance may exist between “yes” and “no” classes
Logistic Regression may struggle with:
Complex non-linear relationships
Highly imbalanced datasets
