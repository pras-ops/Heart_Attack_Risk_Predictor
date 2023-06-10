# Heart Attack Risk Predictor

This repository contains code for predicting the risk of a heart attack using various machine learning algorithms. The prediction is done using the AutoML library Eval ML.

## Project Steps

The following steps are performed in this project:

1.  Data Analysis
2.  Feature Engineering
3.  Standardization
4.  Model Building
5.  Predictions

## Getting Started

To get started with this project, you need to have the following libraries installed:

-   pandas
-   numpy
-   seaborn
-   matplotlib
-   sklearn

## Dataset

The dataset used in this project is stored in a CSV file. You can find the dataset at the following location: heart.csv.

## Data Analysis

The dataset contains the following columns:

-   Age: Age of the patient
-   Sex: Sex of the patient
-   exang: Exercise induced angina (1 = yes, 0 = no)
-   ca: Number of major vessels (0-3)
-   cp: Chest pain type
-   trtbps: Resting blood pressure (in mm Hg)
-   chol: Cholesterol level in mg/dl
-   fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
-   rest_ecg: Resting electrocardiographic results
-   thalach: Maximum heart rate achieved
-   target: Target variable (0 = less chance of heart attack, 1 = more chance of heart attack)

The dataset does not have any null values.

## Model Building

The following machine learning models are used for predictions:

-   Logistic Regression
-   Decision Tree
-   Random Forest
-   K Nearest Neighbor
-   Support Vector Machine (SVM)

The models are evaluated based on their accuracy scores and confusion matrices.

## Report

Based on the evaluation of different machine learning models, the best performing model is **Logistic Regression** with an accuracy of 85%. The confusion matrix for the Logistic Regression model is as follows:



`Confusion Matrix:
[[80  9]
 [13 79]]

Accuracy: 85%` 

This model can be used to predict the risk of heart attacks in patients based on the given dataset.

For more details, refer to the Jupyter Notebook or code files in this repository.
