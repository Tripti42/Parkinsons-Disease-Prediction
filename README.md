# Parkinson's-Disease-Prediction
In this project, we focused on Parkinson's Disease Prediction using a dataset that contains various medical and demographic features for patients. The goal was to predict whether a patient is diagnosed with Parkinson's disease (binary classification: 0 for no, 1 for yes). Below is a detailed step-by-step explanation of what I have done:

 **Data Overview and Understanding**

The dataset has 2,105 records with 35 features, including:
Demographic Information: Age, Gender, Ethnicity, Education Level, BMI, lifestyle factors (Smoking, Alcohol Consumption, etc.
  
Health Information: Medical conditions like hypertension, diabetes, cholesterol levels, and symptoms related to Parkinson's disease (tremor, rigidity, speech problems, etc.
  
Target Variable: The column Diagnosis was used as the target variable, where 0 represents "No Parkinson’s" and 1 represents "Parkinson’s diagnosis."
  
 **Data Preprocessing**
  Before applying machine learning models, "I preprocessed the data to ensure it was clean and suitable for analysis:

Dropped Irrelevant Columns:
  I removed columns like PatientID (unique identifier) and DoctorInCharge (text field containing confidential placeholder data) because they do not contribute to the prediction of Parkinson's diagnosis.
    
Label Encoding for Categorical Variables:
  Columns such as Gender, Ethnicity, and EducationLevel contained categorical values. I used Label Encoding to convert these into numeric representations, making them compatible with the machine learning 
  algorithms.
     
Feature-Target Split:
 In this I have  split the dataset into features (X) and the target variable (y). The feature matrix (X) contains all variables except Diagnosis, and the target vector (y) contains the Diagnosis column.

Data Standardization:
    Since many of the features were on different scales (e.g., Age, Cholesterol levels, BMI), I have  used StandardScaler to standardize the dataset. This ensures that all features contribute equally to the model’s 
    predictions and avoids biases due to different scales.
    
 **Model Training and Evaluation**
 I have  applied  different machine learning models to classify patients as diagnosed or not diagnosed with Parkinson’s disease:

 Decision Tree
 Decision Trees are non-linear models that split data into subsets based on feature conditions. They are interpretable but can easily overfit.

 Random Forest
 Random Forest is an ensemble learning method that builds multiple decision trees and combines their outputs to improve prediction accuracy and reduce overfitting.

  Support Vector Machine (SVM)
SVM is a powerful algorithm that finds a hyperplane in a high-dimensional space that best separates the classes. It performed  well.


** Model Evaluation Metrics**
For each model, we evaluated the performance using:

Accuracy: The percentage of correctly classified instances.
Precision, Recall, and F1-Score: These metrics are especially important in medical data, where misclassifying patients can have serious consequences. Precision measures the accuracy of positive predictions, recall measures how many actual positives were identified, and the F1-Score is the harmonic mean of precision and recall.
