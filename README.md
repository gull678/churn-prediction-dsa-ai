# churn-prediction-dsa-ai
Customer churn, the rate at which customers stop doing business with a company, is a critical metric for many businesses. This project involves processing churn data from a CSV file, utilizing a linked list to store and count churned customers, and applying a logistic regression model to predict customer churn based on features.
This project demonstrates a hybrid approach to solving a real-world problem of customer churn prediction by combining data structures (linked lists) with an AI algorithm (logistic regression).

**Overview**
Customer churn, the rate at which customers stop doing business with a company, is a critical metric for many businesses. This project involves processing churn data from a CSV file, utilizing a linked list to store and count churned customers, and applying a logistic regression model to predict customer churn based on features like age, balance, and credit score.

**Features**
**Linked List Implementation:**

A custom linked list structure is implemented in Python to store and process churn labels (Exited column).
Allows efficient traversal and counting of churned customers.
**AI Integration:**

A logistic regression model is trained on customer features to predict the likelihood of churn.
Model performance is evaluated using accuracy on a test dataset.
**Data Handling:**

Data is read from a CSV file containing customer information and churn labels.
Features such as Age, Balance, and CreditScore are extracted for training the AI model.
**Seamless Integration:**

Combines traditional data structures with modern AI techniques in a single workflow.
Highlights the versatility of Python for both data manipulation and machine learning.
**How It Works
Data Loading:**

Customer churn data is loaded from a CSV file.
The linked list is used to store and traverse churn labels (Exited column).
**Churn Analysis:**

The linked list is used to calculate the total number of churned customers.
**AI Model Training:**

Features are extracted from the CSV file and split into training and testing sets.
A logistic regression model is trained to predict churn based on customer features.
**Evaluation:**

The model's accuracy is measured on the test dataset.
Outputs include the total churn count and the model's prediction accuracy.
**Requirements**
Python 3.x
**Libraries:**
scikit-learn
csv
**Usage**
Place the customer churn data file (Customer-Churn-Records.csv) in the appropriate directory.
Ensure the CSV file contains the following columns: Age, Balance, CreditScore, and Exited.
**Run the script to:**
Count churned customers using the linked list.
Train and evaluate a logistic regression model for churn prediction.
**Outputs**
Number of churned customers stored and processed using a linked list.
Prediction accuracy of the logistic regression model.
**Applications**
Learning data structures like linked lists in a real-world scenario.
Applying machine learning to solve customer retention problems.
Demonstrating the integration of traditional programming concepts with modern AI techniques.
