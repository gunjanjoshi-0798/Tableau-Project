# Healthcare
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/0d70ac68-8731-4732-a425-69ab7ccbbab7)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/48859187-8c96-4636-a5e8-cf9e8204a68d)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/0adc1883-9a25-4ca4-b341-e0dd3ce8fb80)
![image](https://github.com/gunjanjoshi-0798/Tableau-Project/assets/155617045/400a1a21-0c43-423e-b572-8987db8f1862)



## Background
You are a data analyst at HealthStat Solutions, a company specializing in healthcare analytics. You have been given two datasets: 'Patient Medical Records' and 'Hospital Treatment Details'. The 'Patient Medical Records' dataset contains detailed information on patients, including their age, gender, blood type, diagnosis, treatments, admission and discharge dates, and total bills. The 'Hospital Treatment Details' dataset provides insights into the hospitals treating these patients, including the treating doctor, room number, daily costs, treatment types, and recovery ratings.

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
