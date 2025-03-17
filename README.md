# Rainfall Prediction Competition

## Overview
This competition aims to predict the probability of rainfall using a dataset generated from a deep learning model trained on the *Rainfall Prediction using Machine Learning* dataset. While feature distributions closely resemble the original dataset, they are not identical. Participants are encouraged to leverage the original dataset to explore differences and assess whether incorporating it in training improves model performance.

## Dataset Description
The dataset consists of both training and test data:
- **train.csv**: Contains labeled training data with features and a binary target variable (`rainfall`).
- **test.csv**: Contains unlabeled test data, where participants must predict the probability of rainfall.
- **sample_submission.csv**: A sample submission file indicating the expected format for final predictions.

## Objective
The goal is to develop a predictive model that estimates the probability of rainfall for each instance in the test set.

## Submission Format
Your submission file should be a CSV containing two columns:
- `id`: The unique identifier for each test sample.
- `rainfall`: The predicted probability of rainfall (a value between 0 and 1).

Example:
```csv
id,rainfall
1,0.75
2,0.23
3,0.89
```

## Guidelines
- You may use the original *Rainfall Prediction using Machine Learning* dataset to enhance your model.
- Feature engineering and model optimization techniques are encouraged to improve predictive performance.
- Ensure that your submission adheres to the specified format to avoid disqualification.

## Evaluation Metric
Predictions will be evaluated based on **log loss**, which measures the accuracy of probabilistic predictions.

## Getting Started
1. Download the dataset files (`train.csv`, `test.csv`, `sample_submission.csv`).
2. Explore and preprocess the data.
3. Develop and train your machine learning model.
4. Generate predictions for the test dataset.
5. Submit your predictions in the required format.

## Contact & Support
For any inquiries or clarifications, please refer to the competition discussion forum or contact the competition organizers.

Good luck and happy modeling!

