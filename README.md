# Heart-Disease-Prediction-Using-Machine-Learning-Algorithims
•	Project Objective is to develop Efficient model that can predict Heart Disease based on certain features of patients. 

•	In this study, an effective heart disease prediction system (EHDPS) is developed using various Machine Learning Algorithms (Logistic Regression, Decision tree, Random Forest and Navie Bayes) for predicting the risk level of heart disease. Also, accuracies from all the algorithms has been compared for the best prediction model.

•	The proposed system can determine an exact hidden knowledge, patterns and relationships associated with heart disease from a historical heart disease database.

 ## Problem Statement
Let's imagine you are a doctor. You have to diagnose the patient and determine if he has heart disease. In that case, two things will be very important:

If it is heart disease, it should not be judged as normal. An undiagnosed heart disease should not lead to an accident that prevents the patient from receiving appropriate treatment.
In other words, recall becomes a very important metric. Diagnosis results should be well explained in a way that the patient can understand. In other words, you should be able to logically explain to the patient which features influenced your decision.
Data Set Information: Our "goal" predict the presence of heart disease in the patient.The Data Set contains 12 columns or features through which we need to detect the heart Disease.

Source: Dataset from : https://www.kaggle.com/
 
## Features

**Age:** age of the patient [years]

**Sex:** sex of the patient [M: Male, F: Female]

**ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

**RestingBP:** resting blood pressure [mm Hg]

**Cholesterol:** serum cholesterol [mm/dl]

**FastingBS:** fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

**RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]

**MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]

**ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]

**Oldpeak:** oldpeak = ST [Numeric value measured in depression]

**ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

**HeartDisease:** output class [1: heart disease, 0: Normal]
##  Observations from overall EDA:

*   patients with Heart Disease count is **499(55.1%)**
*   patients with No  Heart Disease count is **406(44.9%)**
*   In overall male patients,there are large number of males who are having   Heart Disease
*   In age distribution of dataset most of the people belog to **age 50-60**.
*   Maximum heart disease patients lies between **50-60**.
*   People **having chloestrol level around 200** are highly suffering from heart disease
*   Most of the people having **'ASY'**Type of Cheast pain.
*   Most of the people having **'ASY'** Type of Cheast pain having heart disease.
*   Most of the people having **'0' Fasting_BS**
*   Most of the people having **'0' fasting_BS** having heart disease.
*   Most of the people having **'Normal' Resting_ECG.**
*   Most of the people having **'Normal' Resting_ECG** having heart disease.
*   Most of the people having **'No' ExerciseAngina.**
*   Most of the people having **'YES'ExerciseAngina** having heart disease.
*   Most of the people having **'Flat' ST_Slope.**
*   Most of the people having  **'Flat' ST_Slope** having heart disease.
*   
## Observations of all 5 Algorithms:
1) Accuracy of Logistic Regession is:90.1%

2) Accuracy of Decision Tree is: 85%

3) Accuracy of Random Forest is:89%

4) Accuracy of Random Forest with PCA is:89%

5) Accuracy of Navie Bayes is:91%
## Conclusion:

I studied in breifly about the data, its characteristics and its distribution.

I explored some questions related to Heart Disease.

I investigated in depth about the features which to retain and which to discard.

I performed model training.

I observed metrics for our prediction.

This model now can help us in identifying Heart Disease on the basis of given features.
