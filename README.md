# Hospital Healthcare Management Dashboard

An interactive Power BI dashboard analyzing 2,506 hospital patient records across 10 departments. The report explores patient demographics, department performance, clinical outcomes, patient satisfaction, and treatment costs through five interactive pages.

## Project Overview

This project transforms hospital data into an interactive dashboard to help managers explore patient volume, department performance, clinical outcomes, patient satisfaction, and treatment spending. Each page includes filters for month, department, gender, patient status, and patient type.

## Dashboard Pages

| Page | Description |
|---|---|
| Executive Overview | Patient counts, treatment costs, length of stay, monthly trends, department distribution, and patient status |
| Patient Analysis | Age groups, gender, patient type, geographic distribution, average age, and ratings |
| Department Analysis | Patient volume, length of stay, treatment costs, staff counts, and department summaries |
| Outcomes and Experience | Patient outcomes, readmissions, ICU cases, feedback, and ratings |
| Treatment Costs | Total, average, median, and highest costs, with cost breakdowns by patient type, month, status, department, and age group |

## Key Findings

- **Overall performance:** 2,506 patients, with total treatment costs of 404.5K and an average cost of 161 per patient.
- **Department contribution:** OPD, Rehabilitation, and Surgery account for 71% of patients and 67% of treatment costs.
- **Monthly trends:** March recorded the highest patient volume, with 904 patients and 147K in treatment costs.
- **Patient outcomes:** All 86 recorded deaths occurred in Rehabilitation and Operation Theatre. Rehabilitation accounted for 393 of 493 readmissions.
- **Patient satisfaction:** 96% positive feedback and an average rating of 4.75 out of 5. Oncology and Neurology recorded the lowest positive feedback percentages.
- **High-cost treatments:** 190 treatments costing more than 500 accounted for 8% of patients and 38% of total treatment costs.
- **Length of stay:** OPD averaged 0.1 days, while Gynaecology and Neurology recorded the longest average stays.

## Dataset

**Source file:** `Hospital__Health_Care_Management_Data_set.xlsx`

**Period:** January–December 2007

| Table | Records | Description |
|---|---:|---|
| Detail data dataset | 2,506 | Patient demographics, patient type, status, treatment costs, length of stay, dates, feedback, and ratings |
| Staff_Detail | 262 | Staff IDs and names |
| Department | 10 | Department IDs and names |
| Bed_Detail | 2,847 | Bed IDs and numbers |

The patient table is connected to the Department, Staff, and Bed tables through `Dpt_ID`, `Staff_Id`, and `Bed_ID`.

## Key DAX Measures

- Total Patients
- Inpatient_Count
- Outpatient_Count
- Female Count and Male Count
- Normal Count
- Discharged Patients
- Readmitted Patients
- ICU Patients
- Inpatient Cost %
- Staff Count
- Positive Feedback %
- Negative Feedback %

## Tools and Technologies

- **Power BI Desktop:** Data modelling, DAX measures, interactive visuals, slicers, and page navigation
- **Power Query:** Data cleaning and transformation
- **Microsoft Excel:** Source data






## Author

**Sreeja Akella**

<img width="583" height="331" alt="image" src="https://github.com/user-attachments/assets/9cd5c1d1-6fff-4381-a1fd-86ab28ad661d" />
<img width="588" height="329" alt="image" src="https://github.com/user-attachments/assets/e12f4e89-cf8d-49bf-8393-5d8a02556f2b" />
<img width="597" height="338" alt="image" src="https://github.com/user-attachments/assets/aa8d4f01-89b6-413c-8c59-3fdf10c69df7" />
<img width="587" height="339" alt="image" src="https://github.com/user-attachments/assets/548fdfc7-5659-4601-a3ce-65baf02be9ad" />
<img width="589" height="331" alt="image" src="https://github.com/user-attachments/assets/55fb0d18-df1a-47d8-a96b-22d5e82f2414" />




