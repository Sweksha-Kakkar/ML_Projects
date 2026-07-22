# Loan Approval Prediction
In this project, I worked on a Loan Approval dataset to predict whether a loan will be approved or not.

I first explored and preprocessed the dataset and then applied different Machine Learning classification algorithms to check which model gives better accuracy.

# Data Preprocessing

Before training the models, I performed the following steps:

Checked the dataset using head(), info() and describe().
Checked for missing values.
Checked for duplicate rows.
Visualized the data using histograms and a correlation heatmap.
Removed the name column as it was not useful for prediction.
Removed the city column because it contained a large number of unique values.
Separated the input features and the target column (loan_approved).
Split the data into training and testing sets.
Used StandardScaler for feature scaling.
Models Used
I applied two Machine Learning classification algorithms:

# Logistic Regression
The Logistic Regression model achieved an accuracy of 86.25%.

# K-Nearest Neighbors (KNN)
After that, I applied the KNN Classifier with n_neighbors = 5.

The KNN model achieved an accuracy of 98.75%.

# Accuracy Comparison
Logistic Regression | 86.25%
KNN | 98.75%

# What I Learned
Through this project, I practiced data preprocessing, data visualization, feature scaling, train-test splitting, and applying classification models.

I also compared the performance of Logistic Regression and KNN. In this dataset, KNN performed better and achieved 98.75% accuracy.
