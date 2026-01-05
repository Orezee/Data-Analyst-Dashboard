# Enhancing Data Integrity and Accuracy in Hospital Patient Records 
## Project Summary
This project analyzes  frequent issues with incomplete and inaccurate patient records,including missing demographic information, inconsistent diagnosis data, and incorrect admission or discharge dates. These data gaps are affecting the hospital’s ability to make informed decisions, monitor patient outcomes, and report accurate statistics to health authorities.
## Project Objectives
The primary objectives of this project are to:
* Identify missing, inconsistent, and duplicate patient records
* Assess data accuracy across demographic, clinical, and administrative fields
* Measure the operational impact of poor data quality
* Recommend automation and validation strategies to improve data collection and management
### Tools & Skill Demostrated
- Microsoft Excel (Advanced)
- Power Query for data cleaning and validation
- Dashboard design for executive reporting
### Dataset Overview
Column: 
PatientID, Name, Gender, Age, Diagnosis, Doctor, Ward, State, Admission_Date, Discharge_Date, LOS,LOS Category
### Sample Preview
|PatientID |Name|Gender| Age| Diagnosis| Doctor| Ward| State| |Admission_Date| Discharge_Date| LOS| LOS Category

|P0481|Ahmed Bello|Female|51 |Covid_19|Dr.M.Bello|Emergency|Lagos|2025-03-09| 2025-03-17|  8|  Valid | 

|P0450| Ali Musa| Male|63| Tyhoid| Dr.J.Eze| Surgical| Kano|2023-03-23| 2023-03-23| 10 Valid
### Data Cleaning Process
- Performed in Excel
- Convert date to proper date_time format
- Removed missing and invalid values
- Calculated new calculated column  - Length of Stay (LOS) - LOS Category
  
