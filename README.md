# Patient_Medical_Data_Analysis
Performed Analytics and explained the inferences for Business Problems
A cancer clinic wants to understand how three antineoplastics (i.e. anti-cancer drugs) A, B, and C are given, either as monotherapy (just one drug is given at a time) or in combination with another drug.  The clinic has provided us with two datasets: one gives diagnoses by patient and the other dataset gives treatment dates for these patients for the drugs of interest. None of the patients in this cohort have died to date, and no data is missing.
 
For each question please include:
•	Your code
•	Results of your code.
•	Your thought process or any necessary explanation for each question.
Questions:
 
Question 1: First, the clinic would like to know for which diseases they are seeing patients.
1a) Which types of cancer does the clinic see patients for?
1b) How many patients does the clinic see for each cancer type?
 
Question 2: The clinic wants to know how long it takes for patients to start therapy after being diagnosed, which they consider to be helpful in understanding the quality of care for the patients.  
2a) How long after being diagnosed do cancer patients start treatment for each cancer type?
2b) Are there any patients which are diagnosed but not treated at the practice?
 
Question 3: After being treated with a first line of treatment (a drug or combination of drugs), what proportion of all cancer patients go on to be treated with a second line of treatment? (For more information on the concept of "first-line therapy", please reference https://www.cancer.net/navigating-cancer-care/how-cancer-treated/when-first-treatment-doesnt-work)
 
Question 4:  How does each drug used at the clinic compare in terms of its duration of therapy?
Data format:
DiagnosisSample01.csv
•	PatientID: patient identifier; each patient has a unique PatientID
•	DiagnosisDate: date of diagnosis
•	DiagnosisCode: an ICD9CM diagnosis code.  See more background at http://www.cdc.gov/nchs/icd/icd9cm.htm
•	Diagnosis: a high-level diagnosis type used for reporting purposes
•	IsCancerDiagnosis: flag to indicate whether a diagnosis is cancer related
TreatmentSample01.csv
•	PatientID: patient identifier; each patient has a unique PatientID
•	TreatmentDate: date of treatment
•	DrugCode: an internal drug identifier
