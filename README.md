# Medical-Insurance-Cost-Prediction-Using-ML

![insurance](https://github.com/badarunnisats/Medical-Insurance-Cost-Prediction-Using-ML/assets/109198401/9563997d-0273-4930-9e36-341a69d0d4cd)

# Project Overview

    Hospital ABC, a leading healthcare provider, aims to optimize its resource allocation and improve patient care by understanding the factors influencing medical costs for its patients. To achieve this, Hospital 
ABC has collected a comprehensive dataset containing information about patients' demographics, lifestyle, health status, and medical expenses etc. The dataset includes attributes   such as age, gender, BMI, smoking 
status, region, as well as additional information like occupation, exercise frequency, chronic conditions, and more. How can we predict medical costs for patients based on demographic factors, lifestyle-related
information, health status, insurance plan type, family medical history, distance to the nearest hospital, and primary care physician visits.

# Objectives

 - Explore the relationship between demographic factors (age, gender, region),lifestyle-related information (BMI, smoking status, exercise frequency), and health status (chronic conditions, mental health) with 
   medical costs.
- Investigate the impact of insurance plan type, income level, and family medical history on healthcare expenses.
- Analyze the influence of distance to the nearest hospital and frequency of primary care physician visits on medical charges.
- Develop a predictive model to estimate medical costs for individual patients based on the collected features.
- Evaluate the performance of the predictive model using appropriate metrics such as mean absolute error or root mean squared error.
- Interpret the results and provide actionable insights for Hospital ABC to optimize resource allocation, healthcare planning, and patient support services

# Data Description

 - Age: The age of the patient in years.
 - Sex: The gender of the patient, either 'M' (male) or 'F' (female).
 - BMI (Body Mass Index): A numerical value representing the body mass index of the patient, which is calculated using their weight and height.
- Children: The number of children the patient has.
- Smoker: Indicates whether the patient is a smoker or not, with values 'Yes' or 'No'.
- Region: The geographic region where the patient resides, with values such as 'North', 'South', 'East', or 'West'.
- Occupation: The occupation of the patient, which can be 'White Collar', 'Blue Collar', 'Professional', 'Student', 'Retired', or 'Self Employed'.
- Exercise_Frequency: The frequency of exercise for the patient, such as 'Daily', '2 times/week', '3 times/week', 'Once a week', or 'Rarely'.
- Chronic_Conditions: Any chronic conditions the patient may have, such as 'None', 'Diabetes', 'High Blood Pressure', 'Heart Disease', or 'Arthritis'.
- Insurance_Plan_Type: The type of insurance plan the patient has, which can be 'PPO', 'HMO', or 'HDHP'.
- Marital_Status: The marital status of the patient, either 'Married' or 'Single'.
- Distance_to_Nearest_Hospital: The distance to the nearest hospital from the patient's residence.
- Income_Level: The income level of the patient, categorized as 'Low', 'Medium', or 'High'.
- Family_Medical_History: Indicates whether the patient has a family medical history or not, with values 'Yes' or 'No'.
- Primary_Care_Physician_Visits: The number of visits the patient makes to their primary care physician.
- Mental_Health_Status: The mental health status of the patient, categorized as 'Poor', 'Fair', 'Good', or 'Excellent'.
- Prescription_Medication_Usage: Indicates whether the patient uses prescription medication or not, with values 'Yes' or 'No'.
- Employment_Status: The employment status of the patient, which can be 'Employed', 'Unemployed', 'Self Employed', or missing (NaN).
- Education_Level: The highest level of education attained by the patient, such as 'High School', "Bachelor's Degree", "Master's Degree", 'PhD', or missing (NaN).
- Dietary_Habits: Describes the patient's dietary habits, such as 'Vegetarian', 'Non-Vegetarian', 'Vegan', or missing (NaN).
- Alcohol_Consumption: Indicates the frequency of alcohol consumption by the patient, such as 'Never', 'Occasionally', 'Regularly', or missing (NaN).
- Sleep_Quality: Subjective assessment of the patient's sleep quality, categorized as 'Poor', 'Fair', 'Good', 'Excellent', or missing (NaN).
- Stress_Level: Measures the perceived stress level of the patient, categorized as 'Low', 'Moderate', 'High', or missing (NaN).
- Medication_Adherence: Indicates the patient's adherence to prescribed medications, with values 'Yes', 'No', or missing (NaN).
- Physical_Activity: Additional information on the patient's physical activity level, such as-participation in sports or specific exercise routines, categorized as 'Low', 'Moderate', 'High', or missing (NaN).
- Access_to_Healthcare: Describes the ease of access to healthcare services for the patient, categorized as 'Easy', 'Moderate', 'Difficult', or missing (NaN).
- Social_Support: Measures the level of social support available to the patient, categorized as 'Low', 'Moderate', 'High', or missing (NaN).
- Environmental_Factors: Any environmental factors that may impact the patient's health or healthcare expenses, categorized as 'Low', 'Moderate', 'High', or missing (NaN).
- Genetic_Predisposition: Indicates whether the patient has a known genetic predisposition to certain health conditions, with values 'Yes', 'No', or missing (NaN).
- Health_Literacy_Level: Measures the patient's level of health literacy, categorized as 'Low', 'Moderate', 'High', or missing (NaN).
- Comorbidities: Additional chronic conditions or comorbidities not captured in the "Chronic Conditions" feature, such as 'Asthma', 'Allergies', 'Cancer', 'Obesity', 'Hypertension', 'Other', or missing (NaN).
- Access_to_Telemedicine: Indicates whether the patient has access to telemedicine services for remote consultations, with values 'Yes', 'No', or missing (NaN).
- Emergency_Room_Visits: The frequency of visits to the emergency room by the patient.
- Healthcare_Utilization: Measures the overall utilization of healthcare services by the patient, including hospital admissions, specialist consultations, etc.
- Charges: The medical insurance charges incurred by the patient.

# Dataset Link

 https://docs.google.com/spreadsheets/d/1ac28k9wcw4h5PeQcR751tL_FlJ-gWWU3WFlZlWWPCRY/edit?usp=sharing

# Methods

 - Seek insight from the dataset with Exploratory Data Analysis
 - Performed Data Processing, Data Engineering and Feature Transformation to prepare data before modeling
 - Built a model to predict Insurance Cost based on the features
 - Evaluated the model using various Performance Metrics like RMSE, R2, Testing Accuracy, Training Accuracy and MAE

# Conclusion

- Provide extra resources and support for high-risk age groups, like 40-49 years, with preventive care and health education.
- Design healthcare programs addressing the specific needs of females who face slightly higher charges.
- Create programs for managing BMI and promoting healthy lifestyles, including nutrition counseling and exercise programs.
- Develop region-specific healthcare strategies to address regional health disparities and enhance healthcare infrastructure.
- Invest in programs for managing chronic diseases, including patient education and remote monitoring technologies.
- Educate patients about insurance plans and collaborate with providers to optimize reimbursement processes.
- Prioritize family medical history screening during patient assessments and offer genetic counseling services.
- Ensure healthcare services are accessible to all income levels, possibly through sliding scale fee structures or financial assistance programs.
- Strengthen primary care coordination to optimize healthcare utilization and prevent unnecessary hospitalizations.
- Continuously monitor healthcare data to inform strategic decisions and tailor interventions.
   
