# Healthcare

## Objective
Your mission is to utilize Tableau's robust capabilities to craft a compelling narrative from the provided datasets. This task will encompass thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate aim is to construct an interactive and intuitive dashboard in Tableau that showcases your key discoveries, offering concise, actionable insights into the optimization of hotel operations and performance.

## Data Source

HealthcareDataset1
This dataset contains the following columns:

- PatientID: A unique identifier for each patient. (Primary Key)
- PatientName: Name of the patient.
- Age: Age of the patient.
- Gender: Gender of the patient.
- BloodType: Blood type of the patient.
- Diagnosis: The diagnosis given to the patient.
- Treatment: The treatment provided to the patient.
- AdmissionDate: Date when the patient was admitted.
- DischargeDate: Date when the patient was discharged.
- TotalBill: The total bill amount for the patient's treatment.
- Full Prescription Details: Detailed prescription information including medication names, dosages, frequency, and duration.

HealthcareDataset2
This dataset contains the following columns:

- PatientID: A unique identifier for each patient, corresponding to 'PatientID' in HealthcareDataset1.xlsx. (Foreign Key)
- Hospital: The name of the hospital where the patient was treated.
- DoctorName: Name of the doctor who treated the patient.
- RoomNumber: The room number assigned to the patient.
- DailyCost: The daily cost of the patient's treatment.
- TreatmentType: Type of treatment provided.
- RecoveryRating: A rating of the patient's recovery (out of 10).

## Dashboard Outcome

![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/0d70ac68-8731-4732-a425-69ab7ccbbab7)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/48859187-8c96-4636-a5e8-cf9e8204a68d)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/0adc1883-9a25-4ca4-b341-e0dd3ce8fb80)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/400a1a21-0c43-423e-b572-8987db8f1862)


## Task Performed

1. **Correlation Analysis between Stay Duration and Recovery Rating**: Investigate if there's a correlation between the duration of hospital stay and recovery ratings.
2. **Clustering for Patient Treatment Patterns**: Use clustering to group patients based on treatment patterns and recovery outcomes.
3. **Advanced Calculations for Prescription Analysis**: Analyze the 'Full Prescription Details' to identify the most commonly prescribed medications for each diagnosis.
4. **Hospital Efficiency Analysis**: Measure hospital efficiency based on average stay duration, recovery ratings, and total bill.
5. **Custom Date Parsing for Admission Trends**: Analyze admission trends by parsing 'AdmissionDate' into day of the week and month.
6. **Dynamic Filters for Patient Demographics**: Create dynamic filters to explore data based on patient demographics like age, gender, and blood type.
7. **Time-Series Forecasting for Hospital Admissions**: Use Tableau's forecasting features to predict the number of hospital admissions for the next 6 months. Base your forecast on trends observed in 'AdmissionDate' and various diagnoses.

## Key Insights

- The total number of female patients were 337, male patients were 329 and other patients 334 in 3 years.
  
- The recovery rating for Diabetes is increasing over the years.
- Using the time series forecasting I forcasted the no. of patients for each diagnosis.
- David Moore checks the maximum no. of patients.
- Cedar Senai Clinic is the most expensive hospital followed by Green Valley Medical Center and the least expensive hospital is Silver Oak Medical Plaza.
- Meple Groove Health Facility has the overall highest recovery rating.
- For Diabetes the Cedar Sanai Clinic's Doctor Elizabeth Davis has the highest recovery rating.
- The number patients going for Mental Therapy as treatment type are also increasing over years.

  

