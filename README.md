# Parkinson's-Disease-Prediction



![image](https://github.com/user-attachments/assets/7f293f97-9de5-4231-b7b5-47cbefc7635e)

In this project, we focused on Parkinson's Disease Prediction using a dataset that contains various medical and demographic features for patients. The goal was to predict whether a patient is diagnosed with Parkinson's disease (binary classification: 0 for no, 1 for yes). Below is a detailed step-by-step explanation of what I have done:

**Dataset Overview**
The dataset includes 35 columns with 2,105 records. Below is a summary of the key variables:

**Patient Demographics:**

PatientID: Unique identifier for each patient.

Age: Age of the patients (ranging from 50 to 89 years).

Gender: Gender of the patients (0 = Female, 1 = Male).

Ethnicity: Ethnicity classification (0 to 3, with 3 representing other/mixed ethnicity).

EducationLevel: Education level (ranging from 0 to 3, where 3 is the highest level).

**Lifestyle and Health Factors:**

BMI: Body Mass Index of the patients.

Smoking: Smoking status (0 = Non-smoker, 1 = Smoker).

AlcoholConsumption: Self-reported alcohol consumption.

PhysicalActivity: Frequency of physical activity.

DietQuality: Quality of diet.

**Clinical and Health History:**

FamilyHistoryParkinsons: Family history of Parkinson’s disease (0 = No, 1 = Yes).

TraumaticBrainInjury: History of traumatic brain injury (0 = No, 1 = Yes).

Hypertension, Diabetes, Depression, Stroke: Presence of these conditions.

**Clinical Assessment Scores:**

UPDRS: Unified Parkinson’s Disease Rating Scale score.

MoCA: Montreal Cognitive Assessment score.

FunctionalAssessment: Measure of functional ability.

**Symptom Severity Indicators:**

Tremor, Rigidity, Bradykinesia, PosturalInstability: Indicators of motor symptoms (0 = Absent, 1 = Present).

SpeechProblems, SleepDisorders, Constipation: Non-motor symptoms (0 = Absent, 1 = Present).

**Diagnosis and Treatment:**

Diagnosis: Diagnosis of Parkinson's disease (0 = No, 1 = Yes).

DoctorInCharge: Name of the doctor in charge (anonymized for confidentiality).


 
The dataset is structured to allow an in-depth analysis of Parkinson’s disease, identifying both motor and non-motor symptoms, as well as evaluating the impact of various lifestyle factors.

**Project Objectives**

**Data Exploration**  Gain a detailed understanding of the dataset by exploring distributions, missing values, and basic statistics.

**Feature Correlation**  Determine the relationships between different clinical variables and the diagnosis of Parkinson’s disease.

**Predictive Modeling:**  Develop machine learning models to predict the presence of Parkinson’s disease based on patient features.

**Visualization:**  Create visualizations to help communicate key findings effectively.


**Model Evaluation Metrics**

For each model, we evaluated the performance using:

Accuracy: The percentage of correctly classified instances.
Precision, Recall, and F1-Score: These metrics are especially important in medical data, where misclassifying patients can have serious consequences. Precision measures the accuracy of positive predictions, recall measures how many actual positives were identified, and the F1-Score is the harmonic mean of precision and recall.


In this project, I have implemented various machine learning models to predict Parkinson's disease based on a dataset of medical and demographic factors. After preprocessing the data, I have applied models like  Decision Tree, Random Forest,and  SVM. The Random Forest model provided the best results, with the highest accuracy and precision, making it a strong candidate for predicting Parkinson's disease in this dataset
