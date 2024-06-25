# **Loan Approval Prediction Model**

This repository contains a loan approval prediction model that combines two powerful machine learning algorithms: Random Forest and Logistic Regression. The model is designed to predict the approval status of loan applications effectively by leveraging the strengths of both algorithms.

## **Features**

- **Random Forest for Feature Selection**
  - Identifies and selects the most significant features that influence the loan approval status.
  - Ensures only the most relevant parameters are considered, enhancing the accuracy and efficiency of the prediction model.
- **Logistic Regression for Prediction**
  - Uses the selected features to predict whether a loan application will be approved or rejected.
  - Provides a clear decision-making framework for loan approval.

## **Usage**

1. **Data Preprocessing**
   - Ensure your dataset is cleaned and preprocessed.
   - Handle missing values and encode categorical variables.
2. **Feature Selection with Random Forest**
   - Use the Random Forest algorithm to determine key features.
3. **Prediction with Logistic Regression**
   - Apply the Logistic Regression model using the selected features to predict loan approval status.

## **Installation**

To run this model, you need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn

You can install these dependencies using pip:

```sh
pip install pandas numpy scikit-learn
