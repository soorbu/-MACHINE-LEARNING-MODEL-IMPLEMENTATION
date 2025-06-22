## MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*:  COTECH IT SOLUTIONS

*NAME*:  SURABHI SANJAY KHATALE

*INTERN ID*:  CT04DG167

*DOMAIN*:  PYTHON PROGRAMMING 

*MENTOR*:  VAISHALI SHRIVASTAVA

*DESCRIPTION*--

This project focuses on building a machine learning model to predict whether a patient is likely to be readmitted to the hospital within 30 days of discharge. The dataset used is the "Diabetes 130-US hospitals" dataset from the UCI Machine Learning Repository, which contains over 100,000 hospital records of diabetic patients collected from 1999 to 2008 across 130 U.S. hospitals.

I began by performing thorough data cleaning and preprocessing, which involved handling missing values, removing irrelevant or low-frequency features, encoding categorical variables (both label and one-hot encoding), and grouping ICD-9 diagnosis codes into broader medical categories for better interpretability.

After preparing the dataset, we trained a Logistic Regression model with class_weight='balanced' to address the severe class imbalance — as only a small percentage of patients are readmitted within 30 days. The model was evaluated on accuracy, recall, precision, and F1-score. It achieved an overall accuracy of approximately 65.8%, and more importantly, a recall of 51% for the positive class, meaning it was able to identify over half of the actual readmission cases — a crucial factor in healthcare risk prediction.

This model can serve as a foundational decision-support tool for hospitals aiming to reduce readmission rates, optimize care plans, and proactively follow up with high-risk patients.

# Screenshots
