# Iris Flower Classification with Logistic Regression

## Overview
This Python script demonstrates the use of Logistic Regression for classifying Iris flowers based on their features. The Iris dataset, a popular dataset for machine learning, is used to train and evaluate the model. The script loads the dataset, splits it into training and testing sets, creates a logistic regression model, fits the model to the training data, makes predictions on the testing data, and calculates the accuracy of the model.

## Prerequisites
Make sure you have the required libraries installed. You can install them using the following command:

```bash
pip install scikit-learn
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/rajinmail/iris-logistic-regression.git
cd iris-logistic-regression
```

2. Run the script:

```bash
python iris_logistic_regression.py
```

## Code Description
- **Load Iris dataset:**
  - Loads the Iris dataset from scikit-learn.

- **Data Splitting:**
  - Splits the data into training and testing sets using the `train_test_split` function.

- **Logistic Regression Model:**
  - Creates a logistic regression model using `LogisticRegression` from scikit-learn.

- **Model Training:**
  - Fits the logistic regression model to the training data.

- **Model Prediction:**
  - Makes predictions on the testing data using the trained model.

- **Accuracy Calculation:**
  - Calculates the accuracy of the model using the `accuracy_score` function from scikit-learn.

- **Prints Accuracy:**
  - Displays the accuracy of the logistic regression model on the testing data.

## Results
The script outputs the accuracy of the logistic regression model, providing an indication of how well the model performs on unseen data. You can further modify the script, experiment with different parameters, and explore additional metrics to gain more insights into the model's performance.

Feel free to adapt the code for other datasets or classification problems.
