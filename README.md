# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. With the rapid increase in digital payments, identifying fraudulent activities has become essential to prevent financial loss and ensure secure transactions.

## Objective

The objectives of this project are:

* To build a model that can accurately identify fraudulent transactions
* To handle highly imbalanced datasets effectively
* To minimize false positives and false negatives

## Technologies Used

* Python
* Google Colab
* Scikit-learn
* Pandas
* NumPy
* Matplotlib / Seaborn

## Dataset

The dataset contains anonymized credit card transactions.

Features include:

* Time: Time elapsed between transactions
* Amount: Transaction amount
* V1 to V28: PCA-transformed features
* Class:

  * 0 indicates legitimate transaction
  * 1 indicates fraudulent transaction

The dataset is highly imbalanced, with very few fraudulent transactions compared to normal ones.

## Methodology

### Data Preprocessing

* Handling missing values
* Feature scaling using standardization
* Handling imbalanced data using techniques such as undersampling or oversampling (SMOTE)

### Model Building

Machine learning algorithms used:

* Logistic Regression
* Random Forest
* Decision Tree

### Model Evaluation

Since the dataset is imbalanced, the following metrics are used:

* Precision
* Recall
* F1-Score
* Confusion Matrix

## Results

The model is able to detect fraudulent transactions effectively, with a strong focus on recall to ensure that most fraud cases are identified while maintaining reasonable precision.

## How to Run the Project

1. Open the notebook in Google Colab
2. Upload the dataset if required
3. Run all cells step by step
4. Observe training and evaluation results

## Future Improvements

* Apply advanced algorithms such as XGBoost or Neural Networks
* Improve performance using larger datasets
* Deploy the model as a web application

## Author

* karthik

## Conclusion

This project demonstrates the application of machine learning techniques to detect fraudulent credit card transactions and improve financial security systems.
