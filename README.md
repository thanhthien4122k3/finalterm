## Spam Email Classification with Logistic Regression
This repository contains a complete implementation of a spam email classification system using Logistic Regression. The project utilizes the UCI Spambase dataset to identify spam emails based on features such as word frequencies and other email characteristics.

### Features
 - Data Preprocessing: Handles missing values, detects and addresses skewness, and applies feature selection techniques.
 - Exploratory Data Analysis (EDA): Visualizes dataset properties, such as feature distributions and relationships.
 - Logistic Regression: Implements and evaluates a classification model with high precision and recall.
 - Feature Selection: Reduces the number of features using Recursive Feature Elimination (RFE) for better model performance.
 - 
### Key Results
Accuracy: 92%
Precision and Recall: Both metrics are high, especially for the spam class.
AUC: 0.975, indicating excellent model performance in distinguishing between spam and non-spam emails.

### Setup Instructions
Dependencies: Install required Python libraries using pip install -r requirements.txt (create a requirements file if necessary).
Dataset: Download the dataset from UCI Spambase Repository.
Run: Use Jupyter Notebook or Google Colab to execute the provided script.
