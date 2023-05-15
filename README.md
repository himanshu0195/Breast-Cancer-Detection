# Breast-Cancer-Detection
Breast Cancer Detection using Support Vector Machine

## Overview:

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumours that can be seen via X-ray or felt as lumps in the breast area.

## Objective:

The key challenge against its detection is how to classify tumours into malignant (cancerous) or benign(non-cancerous). I will complete the analysis of classifying these tumours using machine learning (with SVMs) and the Breast Cancer Wisconsin (Diagnostic) Dataset.
Since the labels in the data are discrete, the predication falls into two categories, (i.e., Malignant or benign). In machine learning, this is a classification problem.
Thus, the goal is to classify whether the breast cancer is benign or malignant and predict the recurrence and non-recurrence of malignant cases after a certain period. To achieve this, we have used machine learning classification methods to fit a function that can predict the discrete class of new input.

## Data Set Link:

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## About this dataset:

The collected data has been stored in the Comma Separated Value file data.csv. Each patient in the dataset is uniquely identified by their id. Broadly every tumour is classified into its dimensions, ‘radius’, ‘texture’, ‘perimeter’, ‘area’, ‘smoothness’, ‘compactness’, ‘concavity’, ‘concave points’, ‘symmetry’, ‘fractal dimension’. Each of these dimensions are then further divided into three more subcategories, ‘mean’, ‘se’ and ‘worst’ parameters. Every patient id contains the following variables:

• id: Unique id of every patient 

• diagnosis: Whether the tumour is malignant(M) or benign(B)

• radius: Radius of the tumour (mean of distances from centre to points on the perimeter)

• texture: Texture of the tumour (standard deviation of grey-scale values)

• perimeter: Perimeter of the tumour (perimeter^2 / area - 1.0)

• area: Area of the tumour

• smoothness: Smoothness of the tumour (local variation in radius lengths)

• compactness: Compactness of the tumour

• concavity: Concavity of the tumour. (Severity of concave portions of the contour)

• concave points: Concave points of the tumour (number of concave portions of the contour)

• symmetry: Symmetry of the tumour

• fractal dimension: Fractal Dimension of the tumor ("coastline approximation" - 1)
