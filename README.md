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
### Key Insight
- A significant number of patients have no assigned Doctors, making it difficult to track care responsibility and delaying clinical reviews. Also, accountability will be difficult in case of complications (1.20%). 
- Analysis of the Length of Stay (LOS) Category by Patient ID shows that 76.20% of patient records are valid, while 23.80% are invalid. It contains date inconsistencies that prevent the accurate calculation of the Length of Stay. Such a high proportion of invalid LOS data raises concerns about data quality, workflow efficiency, and the reliability of operational reporting.
- Missing 18.8% of discharge records creates operational inefficiency, financial losses, compliance challenges, and clinical risks for the hospital. Without accurate discharge dates, beds may appear occupied when they are actually free, causing a delay in giving those beds to new patients. This leads to longer wait times for both emergency and scheduled admissions, ultimately lowering hospital efficiency and patient satisfaction.
