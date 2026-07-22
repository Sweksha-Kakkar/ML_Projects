# ML_Projects

## PROJECT_1

#  1 Titanic Survival Prediction

This is a Machine Learning project that predicts whether a passenger survived the Titanic disaster based on various features such as age, gender, passenger class, and fare.

##  Project Files

- `Titanic_Survival_Prediction.ipynb` - Contains data analysis, preprocessing, model training, and prediction.
- `titanic.csv` - Dataset used for training and analyzing the model.

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

##  Machine Learning Models Used

In this project, I implemented and compared the following Machine Learning classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

These models were trained and tested to predict the survival of passengers and compare their performance.

##  Project Objective

The objective of this project is to understand the basic Machine Learning workflow and build classification models that can predict passenger survival using the Titanic dataset.









## PROJECT_2 

# 2 Ford Car Price Prediction

This is my second Machine Learning project. In this project, I worked with the Ford car dataset to practice data analysis, data visualization, and Machine Learning.

The main objective was to understand the dataset and predict car prices using different features.

## What I Did

- Loaded and explored the Ford car dataset
- Checked the structure and information of the dataset
- Performed basic data analysis
- Created different graphs to understand the data
- Used Seaborn and Matplotlib for data visualization
- Created a correlation heatmap to understand relationships between numerical features
- Prepared the data for model training
- Split the dataset into training and testing sets
- Applied Linear Regression
- Trained the model and made price predictions

## Machine Learning Model Used

- Linear Regression

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## What I Learned

Through this project, I learned and practiced:

- How to explore and understand a real-world dataset
- How to visualize data using different graphs
- How to use a heatmap to understand correlations between features
- How to prepare data before training a Machine Learning model
- How to split data into training and testing sets
- How to implement a Linear Regression model
- How to use a trained model for prediction




## PROJECT_3

# Loan Approval Prediction

In this project, I worked on a Loan Approval dataset to predict whether a loan will be approved or not.

I first explored and preprocessed the dataset and then applied different Machine Learning classification algorithms to check which model gives better accuracy.

## Data Preprocessing

Before training the models, I performed the following steps:

- Checked the dataset using `head()`, `info()` and `describe()`.
- Checked for missing values.
- Checked for duplicate rows.
- Visualized the data using histograms and a correlation heatmap.
- Removed the `name` column as it was not useful for prediction.
- Removed the `city` column because it contained a large number of unique values.
- Separated the input features and the target column (`loan_approved`).
- Split the data into training and testing sets.
- Used `StandardScaler` for feature scaling.

## Models Used

I applied two Machine Learning classification algorithms:

### Logistic Regression
The Logistic Regression model achieved an accuracy of **86.25%**.

### K-Nearest Neighbors (KNN)
After that, I applied the KNN Classifier with `n_neighbors = 5`.

The KNN model achieved an accuracy of **98.75%**.

## Accuracy Comparison

Logistic Regression | 86.25% 
KNN | 98.75% 

## What I Learned

Through this project, I practiced data preprocessing, data visualization, feature scaling, train-test splitting, and applying classification models.

I also compared the performance of Logistic Regression and KNN. In this dataset, KNN performed better and achieved **98.75% accuracy**.


