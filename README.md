#Breast Cancer Diagnosis Prediction Using Random Forest


Project Overview
This project focuses on predicting whether a tumor is malignant or benign using the Breast Cancer Wisconsin Dataset. The goal is to build a robust machine learning model that can accurately classify tumors based on various features related to cell characteristics. I chose a Random Forest Classifier for this task due to its ability to handle complex datasets efficiently and provide high accuracy.

#Dataset
The dataset consists of several features extracted from images of cell nuclei, such as:

Radius
Texture
Perimeter
Area
Smoothness
Compactness
Concavity
Symmetry
The target variable is the diagnosis column, which has two values:

M (Malignant)
B (Benign)
You can find more details about the dataset here.

Steps Involved
#Data Preprocessing:

Removed irrelevant columns like id and Unnamed: 32.
Converted the diagnosis column into a binary format where Malignant (M) = 1 and Benign (B) = 0.
Feature Selection:

Used all relevant numerical features such as radius_mean, texture_mean, etc.
Model Implementation:

#Implemented a Random Forest Classifier.
Split the data into training and testing sets (80% training, 20% testing).
Model Evaluation:

The model achieved an accuracy of 94.73% on the test data.
Other metrics such as precision and recall were also used to ensure balanced predictions.
Results
#The model's accuracy of 94.73% demonstrates its effectiveness in predicting tumor categories. This result highlights the potential of using machine learning to assist in making accurate classifications based on data features.
