
# Hotel Booking Cancellation Prediction

This repository contains a Jupyter Notebook that explores and predicts hotel booking cancellations. The project utilizes a dataset of hotel reservations and applies machine learning techniques to predict whether a booking will be canceled.

## Overview

The project aims to provide insights into the factors influencing hotel booking cancellations and to develop predictive models that can assist hotel management in making informed decisions. It involves data preprocessing, exploratory data analysis, model training, and evaluation using K-Nearest Neighbors (KNN) and Decision Tree classifiers.

## Dataset

The dataset used in this project is `Hotel_Reservations_Encoded.xlsx`, which includes various features related to hotel bookings. Key features include customer details, booking information, and the target variable 'booking_status'.

## Key Steps

1. **Data Preprocessing**: Cleaning, encoding, and splitting the dataset into training and testing sets.

2. **Model Development**: Implementing and evaluating KNN and Decision Tree models for predicting booking cancellations.

3. **Hyperparameter Tuning**: Using GridSearchCV for optimizing model parameters.

4. **Class Imbalance Handling**: Applying SMOTE (Synthetic Minority Over-sampling Technique) to improve model performance on imbalanced data.

5. **Model Evaluation**: Comparing model performances based on accuracy, precision, and recall.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, scikit-learn, imbalanced-learn

## Usage

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook and execute the cells to see the analysis and results.

## Results

- The Decision Tree model generally outperforms the KNN model.
- Hyperparameter tuning enhances model performance.
- The application of SMOTE helps in addressing the class imbalance issue, particularly improving the KNN model's performance in identifying the minority class.

## Contributing

Contributions, issues, and feature requests are welcome. 

