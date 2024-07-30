# Diabetes-Prediction-Using-Gradient-Boosting

This project aims to predict whether a person has diabetes based on various health metrics. The prediction model is built using the Gradient Boosting algorithm. 

## Dataset

The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset/data).  It includes various health-related metrics such as gender, age, hypertension, heart disease, smoking history, BMI, HbA1c level and blood glucose level.

## Features

- **Data Preprocessing:** Handling both numerical and categorical features using StandardScaler and OneHotEncoder.
- **Model Training:** Gradient Boosting Classifier is used to train the model.
- **Evaluation Metrics:** The model's performance is evaluated using Accuracy, Precision, Recall, F1 Score, and ROC AUC Score.
- **Visualization:** Confusion matrix and ROC curve are plotted to visualize the model's performance.
- **Manual Input Prediction:** Users can manually input health metrics to get a prediction on whether they have diabetes.

## Model Used
### Gradient Descent
- Gradient descent calculates the gradient of the error function with respect to each parameter and updates them in the direction that reduces the error  until the model converges to an optimal set of parameters that best fits the training data.

## Evaluation Metrics

The model is evaluated using the following metrics:
- **Accuracy:** Overall correctness of the model.
- **Precision:** Proportion of positive identifications that were actually correct.
- **Recall:** Proportion of actual positives that were identified correctly.
- **F1 Score:** Harmonic mean of Precision and Recall.
- **ROC AUC Score:** Area under the ROC curve, which provides an aggregate measure of performance across all classification thresholds.

## Visualization

The script generates the following visualizations:
- **Confusion Matrix:** Shows the true positive, true negative, false positive, and false negative predictions.
- **ROC Curve:** Plots the True Positive Rate against the False Positive Rate.
