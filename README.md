# Medical-Insurance-Cost-Prediction-Using-ML

![insurance](https://github.com/badarunnisats/Medical-Insurance-Cost-Prediction-Using-ML/assets/109198401/9563997d-0273-4930-9e36-341a69d0d4cd)

# Project Overview

Hospital ABC, a leading healthcare provider, aims to optimize its resource allocation and improve patient care by understanding the factors influencing medical costs for its patients. To achieve this, Hospital 
ABC has collected a comprehensive dataset containing information about patients' demographics, lifestyle, health status, and medical expenses etc. The dataset includes attributes   such as age, gender, BMIsmoking 
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

https://docs.google.com/spreadsheets/d/1iAE4VAWqbz5WFX9_BQ5P6piQzR1GX0fkHAnEP9Ux69E/edit?usp=sharing

# Methods

 - Seek insight from the dataset with Exploratory Data Analysis
 - Performed Data Processing, Data Engineering and Feature Transformation to prepare data before modeling
 - Built a model to predict Insurance Cost based on the features
 - Evaluated the model using various Performance Metrics like RMSE, R2, Testing Accuracy, Training Accuracy and MAE

# Conclusion

**1. Enhance Healthcare Access:**
Make it easier for everyone to get medical help by offering more telemedicine services and addressing issues like transportation and costs. Improve telemedicine services by offering more options and explaining patients how to use them.

**2. Promote Healthy Eating:**
Encourage people to eat healthier foods by sharing information and providing resources about good nutrition.

**3. Raise Awareness for Healthy Living:**
Spread the word about healthy lifestyle choices through campaigns. This includes quitting smoking, learning about nutrition, and managing stress.

**4. Provide Social Support:**
Offer help and companionship to those who need it, so they don't feel alone or isolated.

**5. Improve the Environment:**
Make changes to the environment, like improving air quality and adding green spaces, to make people healthier.

**6. Offer Genetic Advice:**
Provide counseling and screening for people with a family history of certain diseases to help them manage their health better.

**7. Educate People About Health:**
Teach people how to understand health information and make good decisions about their health.

**8.Manage Multiple Health Problems:**
Create plans to help people with more than one health problem get the care they need and avoid getting sicker.

**9. Preventive Care:**
Encourage regular check-ups and vaccinations to stop people from getting sick in the first place.

**10. Financial Help:**
Find ways to help people pay for medical bills if they don't have much money. Help people understand their insurance options and get the right coverage for their medical needs.

**11. Use Data to Decide:**
Look at information about patients to figure out who needs help the most and where to spend money to help them.
bly through sliding scale fee structures or financial assistance programs.
- Strengthen primary care coordination to optimize healthcare utilization and prevent unnecessary hospitalizations.
- Continuously monitor healthcare data to inform strategic decisions and tailor interventions.
   
