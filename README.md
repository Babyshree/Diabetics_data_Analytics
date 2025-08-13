# Diabetics_data_Analytics
## Overview
This project analyzes the **diabetic_data.csv** dataset to identify factors influencing **hospital readmission rates** for diabetic patients.  
It covers **data cleaning, feature engineering, exploratory data analysis (EDA), statistical correlations**, and **insight generation** to support hospital decision-making.

## About the dataset
encounter_id – Unique identifier for each hospital visit/encounter.
patient_nbr – Unique identifier for each patient (patients can have multiple encounters).
race – Patient’s race (e.g., Caucasian, AfricanAmerican, Asian, etc.).
gender – Patient’s gender (Male, Female, Unknown/Invalid).
age – Age group of the patient (in 10-year bins, e.g., 50–60).
weight – Patient’s weight (in weight bands); may contain missing values.
admission_type_id – Numeric code for admission type (e.g., Emergency, Elective, Urgent).
discharge_disposition_id – Numeric code for discharge status (e.g., home, transferred, expired).
admission_source_id – Numeric code for where the patient was admitted from (e.g., physician referral, transfer from another hospital).
time_in_hospital – Length of stay in days for the encounter.
payer_code – Insurance/payment code (e.g., Medicare, Medicaid, Private).
medical_specialty – Specialty of the admitting physician (e.g., Cardiology, Endocrinology).
num_lab_procedures – Number of lab tests performed during the encounter.
num_procedures – Number of non-lab medical procedures performed.
num_medications – Number of medications prescribed during the encounter.
number_outpatient – Number of outpatient visits in the year before the encounter.
number_emergency – Number of emergency room visits in the year before the encounter.
number_inpatient – Number of inpatient visits in the year before the encounter.
diag_1 – Primary diagnosis code (ICD-9).
diag_2 – Secondary diagnosis code (ICD-9).
diag_3 – Additional diagnosis code (ICD-9).
number_diagnoses – Total number of diagnoses recorded for the encounter.
max_glu_serum – Maximum glucose serum test result (categories: >200, >300, normal, none).
A1Cresult – A1C test result (categories: >7, >8, normal, none).
metformin – Change status of metformin prescription (No, Steady, Up, Down).
repaglinide – Change status of repaglinide prescription.
nateglinide – Change status of nateglinide prescription.
chlorpropamide – Change status of chlorpropamide prescription.
glimepiride – Change status of glimepiride prescription.
acetohexamide – Change status of acetohexamide prescription.
glipizide – Change status of glipizide prescription.
glyburide – Change status of glyburide prescription.
tolbutamide – Change status of tolbutamide prescription.
pioglitazone – Change status of pioglitazone prescription.
rosiglitazone – Change status of rosiglitazone prescription.
acarbose – Change status of acarbose prescription.
miglitol – Change status of miglitol prescription.
troglitazone – Change status of troglitazone prescription.
tolazamide – Change status of tolazamide prescription.
examide – Change status of examide prescription.
citoglipton – Change status of citoglipton prescription.
insulin – Change status of insulin prescription.
glyburide-metformin – Change status of combination glyburide-metformin prescription.
glipizide-metformin – Change status of combination glipizide-metformin prescription.
glimepiride-pioglitazone – Change status of combination glimepiride-pioglitazone prescription.
metformin-rosiglitazone – Change status of combination metformin-rosiglitazone prescription.
metformin-pioglitazone – Change status of combination metformin-pioglitazone prescription.
change – Whether there was a change in diabetes medication (Ch = changed, No = no change).
diabetesMed – Whether any diabetes medication was prescribed (Yes or No).
readmitted – Whether the patient was readmitted (No, >30 days, or <30 days).