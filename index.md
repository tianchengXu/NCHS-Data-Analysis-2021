# Analysis of Healthcare Operation Efficiency Under COVID-19 with National Center for Health Statistics Data



Tiancheng Xu, Pinchao Chen, Gloria Wang, Shreya Deshmukh, Pranav Gupta

December, 2021

## The Goal

To develope a series of dashboards based on 550k+ data from NCHS (National Center for Health Statistics) during COVID-19 using Tableau; to visualize and to analyze nationwide patient demographics, drug consumption and trends in top diagnoses; to undetstand state-wise operational efficiency by healthcare specification, and to discover opportunities for operation improvement and geographic areas that require attention.

---

We explored the data from a visual perspective to provide the management with some insights into the overall status, operation performance, potential issues, and areas of improvement of the healthcare providers across the country.


### Patient Overview

<img width="1088" alt="image" src="https://user-images.githubusercontent.com/63265930/172221980-19072d86-bcc9-4d77-ba4f-7d5bd64c487d.png">

The analysis aims to understand the patient base to improve the services’ efficacy. First, we break down the patient numbers by age, gender, race, and ethnicity. To get a general overview, the dashboard provides the top reasons for visiting a hospital. Progress visit i.e., follow-up visits is the top reason. Drilling down “Progress visit”, we observe “Depressive Disorder” as the main reason for recurrence of patient visits. To glean insights, analysis of the top 3 diseases per age category has been provided, leveraging ICD data points. Based on this, we notice that “Depressive disorder” shows an upward trend, peaking in the age category of 45-64 years. Furthermore, it has the second-largest number of diagnoses in the Diagnosis & Drug dashboard. We can take a deeper view by clicking “Depressive disorder” in the Top 5 Diagnoses bar chart, this filters data to patients who have depression and we are able to see Top 5 Drugs Prescribed and a timeline trend for depression. Apparently, there was an increasing trend for the number of depression visits until April 2021 because of the Covid-19 lockdown. Then, the visits dropped because the lockdown was over. Therefore, National Health Group management could better allocate supply for those drugs throughout the nation if another incident causes visits for depression to rise. Also, similar analyses could be done on other diagnoses.![image](https://user-images.githubusercontent.com/63265930/172483303-0cf95285-f65f-4ae3-ae9b-c3d076e2353e.png)


### Patient Distribution

<img width="1099" alt="image" src="https://user-images.githubusercontent.com/63265930/172223144-ad5cd5a4-5cf0-4812-9c95-2efaf0bf829d.png">


### Diagnosis & Drug Analysis

<img width="1089" alt="image" src="https://user-images.githubusercontent.com/63265930/172223602-180e0ef6-e982-4073-a521-b915d654aac2.png">


### Operation Efficiency Analysis

<img width="1031" alt="image" src="https://user-images.githubusercontent.com/63265930/172224816-cd9179b7-0782-45a3-9132-eb29e05756b4.png">


### Payer Type Analysis

<img width="1081" alt="image" src="https://user-images.githubusercontent.com/63265930/172226051-ccc88ec9-f448-4f3a-a632-0a9f053a502c.png">





### Link to the Tableau dashboard
https://public.tableau.com/app/profile/tiancheng.xu/viz/NationalHealthcareDataAnalysis/NationalHealthcareDataAnalysis
