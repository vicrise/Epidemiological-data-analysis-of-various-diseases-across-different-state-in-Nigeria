# Epidemiological-data-analysis-of-various-diseases-across-different-states-in-Nigeria
### PROJECT OVERVIEW
The dataset contains 284,484 records of individuals diagnosed with various diseases, including Meningitis, Marburg Virus, Measles, Cholera, and Rubella Mars. It includes demographic details (name, gender, age, location), disease information (health status, report outcome), and time-based data (report date, year of birth). 
### PROBLEM STATEMENT 
The various diseases recorded in this dataset are the major diseases that are common in Nigeria, and they vary in different location 
The problems this project addresses are how these various infectious diseases spread across different states and settlements, what the demographic distribution of affected individuals is, and what the health outcomes of reported cases (alive vs. dead) 
### OBJECTIVES
1.	 To identify which genders are most affected
2.	To determine how diseases are distributed across states and rural/urban areas
3.	To compare survival rates across different diseases 
4.	To analyze how disease cases fluctuate over the years
### DATA SOURCE 
kaggle
### METHODOLOGY
#### TOOL USED: Power BI
#### DATA CLEANING PROCESS AND TRANSFORMATION: 
The dataset was clean, but I checked for any inconsistencies, duplicates, and errors 
### DAX FUNCTION 
-	TOTALFEMALE = CALCULATE( COUNT(Disease_dataset[gender]),Disease_dataset[gender]= "female")
-	TOTALMALE = CALCULATE( COUNT(Disease_dataset[gender]),Disease_dataset[gender]= "male")
### DATA ANALYSIS
Identify patterns and how this various disease is distributed among individuals, states, and settlements across the country.
### KEY INSIGHTS AND RECOMMENDATION

![Screenshot (132)](https://github.com/user-attachments/assets/65a2424a-d96c-4d98-9804-3fe3097b656c)
### Insights 
Count of disease reported by individuals 
- The highest recorded cases were in 2013 (28,745) and 2016 (28,638), indicating significant increases in disease counts during these years. The lowest disease count appears to be around 2011 (28,187) and 2015 (28,262). In 2016, there was a downward trend, reaching 28,428 in 2018. This might indicate better healthcare interventions or underreporting.
### Recommendations:
- If recent declines are due to improved healthcare measures, these should be reinforced and scaled.
- We should advise the rural settlement to always report an incident of disease in their community to a healthcare provider

![Screenshot (134)](https://github.com/user-attachments/assets/26d61781-7835-4d87-bdd7-41cacc7dbb68)
### Insights 
 - The distribution between males and females is relatively consistent across all diseases.
- The number of affected individuals is almost identical for males and females, with slight variations across different diseases. like:
Cholera and malaria affected females (14.6k) more than males (13.9k)
- Diarrhea, Marburg Virus, and Meningitis show slightly higher numbers for females (14.8K vs. 13.7K), but the difference is marginal.
 We recorded a high number of diseases like measles and rubella mars 
### Recommendations:
 - Public health initiatives should target both males and females equally in prevention campaigns for all listed diseases.
 - Resources should be allocated efficiently without bias toward one gender since the data shows no significant disparity.
- Investigating regional or environmental factors might uncover underlying reasons for the marginal differences between the genders in certain diseases (e.g., Cholera, Malaria).
 - With the consistent prevalence across genders, the focus should be on strengthening awareness campaigns for these diseases, particularly for those with the highest recorded cases (Measles and rubella mars).
   
   ![Screenshot (139)](https://github.com/user-attachments/assets/7dbf58c8-2988-4602-bba7-8b0fe0dfc7b3)
   ### Insights 
  - States with Highest Disease Burden (Total Cases):
- Niger - 7842 cases 
- Ondo - 7835 cases
- Kano - 7822 cases
- Bayelsa - 7797 cases
- These states consistently recorded high numbers across multiple diseases.
- States with Lowest Disease Burden (Total Cases):
- Cross river - 7524 cases
- Plateau - 7545 cases
- Borno - 7564 cases
- Ekiti - 7560 cases
- Marburg Virus:
- Abia (849) and Benue (831) have the highest numbers.
- Meningitis:
- Benue (849) and Ebonyi (822) are leading among others.
### Recommendations:
 - Allocate more medical resources and awareness programs to states like Niger, Ondo and others where high cases are recorded.
 - Implement targeted vaccination and sensitization campaigns in Borno, Adamawa and Bauchi to tackle Yellow Fever and in Ebonyi and Benue to tackle Meningitis.
 -  Governments should deploy real-time disease surveillance systems in Northern Nigeria, where Meningitis and Cholera spikes are evident.
 - Set up mobile clinics and disease response units in the Southern belt for Viral Hemorrhagic Fever and Marburg Virus.
     
![Screenshot (137)](https://github.com/user-attachments/assets/5c172a7e-43c2-4ceb-9d0f-8075fcab12bb)
### Insights 
- The survival rates are very similar across every disease, but there are variations 
For example, 14268 patients survived cholera while 14321 patients did not survive
14365 patients survived malaria while 14170 patients did not survive and soon 
- This suggests that some patients have access to medical facilities while others do not have access to it 
### Recommendations 
- Hospitals should be closer to the people so they can access fast medical facilities
### CONCLUSION 
- Individuals should always report any incident of disease outbreak in their community to the healthcare provider
- The government should invest in the healthcare sector so that those especially in the rural area can have access to an affordable healthcare facility 
- Vaccines, medications and adequate treatment should be given to individuals that have one disease or the other
  - [INTERACTIVE DASHBOARD](https://app.powerbi.com/groups/me/reports/2711ccb3-cf38-48c4-8ef3-271ea712db52/dc5dfb9c622b81cc0c38?experience=power-bi)




