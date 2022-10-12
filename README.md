# Stroke Prediction with Machine Learning
> An ischemic stroke occurs when the blood supply to part of the brain is interrupted or reduced, preventing brain tissue from getting
oxygen and nutrients. Brain cells begin to die in minutes. A stroke is a medical emergency, and prompt treatment is crucial. Early action
can reduce brain damage and other complications. According to the World Health Organization (WHO) stroke is the 2nd leading cause of death
globally, responsible for approximately 11% of total deaths.

> **This dataset is used to predict whether a patient is likely to get a stroke based on the input
parameters like gender, age, various diseases, and smoking status. Each row in the data provides
relevant information about the patient.**

> According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

# Dataset Description
As this work is based on a human stroke predictor, the data set was to predict stroke based on 5110 entries of patients having 10 columns of data they have provided carrying “id, gender, age, hypertension, marital status, work type, residence type, average glucose level, body
mass index and smoking status and stroke chances”. Here by fitting the data with label and feature according to the information, here stroke column(L) will be counted as label and Column B to K will be considered as feature.

## Attribute Information
+ id: unique identifier
+ gender: "Male", "Female" or "Other"
+ age: age of the patient
+ hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
+ heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
+ ever_married: "No" or "Yes"
+ work_type: "children", "Govt_job", "Never_worked", "Private" or "Self-employed"
+ Residence_type: "Rural" or "Urban"
+ avg_glucose_level: average glucose level in blood
+ bmi: body mass index
+ smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
+ stroke: 1 if the patient had a stroke or 0 if not *Note: "Unknown" in smoking_status means that the information is unavailable for this patient

# Data Preprocessing Techniques Applied
