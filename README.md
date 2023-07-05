# Stroke Prediction Using Data Mining

This project is part of the ADS-502 Applied Data Mining course in the Master's in Applied Data Science Program at the University of San Diego
Project Title: Stroke Risk Prediction

### Installation
To use this project, first clone the repo on your device using the command below
```
git init
git clone https://github.com/hunterblum/Stroke-Prediction.git
```

### Objective: 

The main purpose of this project is to develop a classification machine learning model to predict stroke risk.  This is done using a data set consisting of 11 predictor variables that cover lifestyle, age, and overall health.  Our project focused on constructing a sensitive and accurate model to identify what patients are most likely to have a stroke to capitalize on the success of early prevention techniques.  The data was collected from Kaggle.com and consisted of 12 attributes describing traditional stroke risk factors.

### Partners:
* Andrew Kim
* Benjamin Earnest
* Hunter Blum

Methods Used:
* Data Mining
* Predictive Modeling
* Data Visualization
* Programming
* Machine Learning
* Inferential Statistics

### Technologies:
* R

### Project Description:
Caused by vascular injuries in the brain, strokes are the second leading cause of death and disability in the world. In the United States, somebody dies of a stroke every 3.5 minutes resulting in $53 billion in costs annually. However, prevention strategies can have a massive impact, with current prevention techniques mitigating up to 80% of strokes. A major part of beginning prevention is identifying patients who are at risk of stroke. Current model accuracies for predicting strokes in patients can range from 88% to 97%. This project considered existing data based on patient risk factors, identified the key predictor variables, and evaluated model efficacy. The goal was to identify which modeling algorithm, provided the most accurate and sensitive predictions of strokes in patients when tested with novel data. 

The data set is in .csv format and can be found on kaggle.com at https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset.  

### Attribute information:

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
