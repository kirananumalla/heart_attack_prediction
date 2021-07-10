# Heart Attack Binary Classification Take-Home Assignment

You have been given the task of building a binary-classifier that predicts whether a person is to have a heart attack or not given a dataset of 303 patients and 13 variables (14 columns in total including the target variable) – please find the column definitions below:

### Column Definitions:

- **age**: Patient age.
- **gender**: Patient gender (Unspecified).
- **chest_pain_type**: Chest Pain type.
        Typical angina
        Atypical angina
        Non-anginal pain
        Asymptomatic
- **rest_blood_pressure**: Resting blood pressure (in mm Hg).
- **cholesterol**: Cholesterol in mg/dl fetched via BMI sensor.
- **fast_blood_sugar**: Fasting blood sugar > 120 mg/dl.
- **rest_ecg**: Resting electrocardiographic results.
        Normal.
        Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV).
        Showing probable or definite left ventricular hypertrophy by Estes' criteria.
- **max_heart_rate**: Maximum heart rate achieved.
- **ex_ind_ang**: Exercise induced angina (Yes, No).
- **prev_peak**: Old peak.
- **slope**: Slope.
- **vessels_num**: Number of major vessels (0-3).
- **thal_result**: Thalium Stress Test result.
- **output**: 0 = less chance of heart attack, 1 = more chance of heart attack.



To perform the predictions, you are required to carefully explore the dataset and select the variables that you deem as the most relevant.<br>
There also are no restrictions in terms of:<br>
•	The number of features that are ultimately chosen to build the model i.e., you are more than welcome to create new features based on the already-existing ones if you so wish.<br>
•	How you decide to perform the train-test split of the data.<br>
•	The models you ultimately select and compare against.<br>
It is worth mentioning that the objective of this assignment is not to maximise the performance of the model, but instead to enable us to gain a deeper understanding of your analytical abilities (EDA, feature engineering, and feature selection) and technical skills (model selection, training, and interpretation).<br>
Lastly, we recommend the assignment to be presented and sent in Jupyter Notebook format (.ipynb), as its interactive and cell-based interface allows for a more user-friendly and legible experience. However, if you feel more comfortable with writing code in regular Python files (.py), you are also more than welcome to send it in such format.
Best of luck!
