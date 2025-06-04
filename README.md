
# Logistic Regression for Diabetes Prediction

This project demonstrates the use of **Logistic Regression** to predict diabetes status based on basic health indicators.

## Features

* Uses **Logistic Regression** for binary classification.
* Splits data into training and testing sets.
* Evaluates the model using **accuracy score**.

## Dataset

* The dataset contains 10 synthetic samples with the following 5 features:

  * `Age`: Age of the person (years)
  * `BMI`: Body Mass Index
  * `Blood Pressure`: Measured in mmHg
  * `Glucose Level`: Measured in mg/dL
  * `Family History`: 1 = Yes, 0 = No (binary indicator)

* Target variable:

  * `Diabetes`: 1 = Yes, 0 = No (whether the person has diabetes)

## Code Explanation

* The data is manually defined in the script as two Python lists: `x` for features and `y` for labels.
* Data is split into **80% training** and **20% testing** using `train_test_split`.
* A **Logistic Regression** model is trained using `scikit-learn`.
* Predictions are made on the test set.
* Model performance is evaluated using `accuracy_score`.

## How to Run

1. Install required packages:

   ```
   pip install scikit-learn pandas
   ```

2. Run the Python script:

   ```
   python logistic_regression_diabetes.py
   ```

3. The output will include predicted values and the accuracy of the model.

## Output

Example output:

```
Predictions: [1 0]
Accuracy: 1.0

