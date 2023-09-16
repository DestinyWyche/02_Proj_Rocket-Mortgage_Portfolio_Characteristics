# Rocket Mortgage Portfolio Characteristics

## Purpose of Project

For this project, I explored loan-level data for the Rocket Mortgage financial institution to identify loan and borrower characteristics using **Excel and Tableau**. All files referenced can be found at this [link](https://drive.google.com/drive/folders/15DJZE1g5xDiOCeXR1o2XEJahfrOaEruf?usp=sharing)

## Data Analysis Process

### Asking the question

In this project, I answered the following questions about the loans and borrowers:

- Loans  
  - What was the total loan volume in 2022?  
  - What is the loan volume by loan type?  
  - What is the loan volume by loan purpose?
  - What is the loan volume by state?
- Borrowers
  - What was the total borrower volume in 2022?
  - What is the borrower volume by age group?
  - What is the loan volume by borrower occupancy type?
  - What is the borrower volume by state?

### Preparing the data

- Data was collected from Home Loan Disclosure Act(HMDA) Modified Loan/Application Register (LAR) which can be found by clicking this [link](https://ffiec.cfpb.gov/data-publication/modified-lar/2022)

### Processing the data  

- Raw data was an csv file with delimiters, so I used the **text to columns function** in **Excel** to separate data in readable rows and columns.
- Some columns had data field numbers which corresponded to certain descriptions found in the online data schema (which can be found at this [link](https://ffiec.cfpb.gov/documentation/publications/modified-lar/modified-lar-schema)). So, I used **VLOOKUP function** to create a new column that defined these data field numbers    
  
![image](https://github.com/DestinyWyche/02_Proj_Rocket-Mortgage_Portfolio_Characteristics/assets/111715383/e86e8577-4fa4-47fb-b579-0d993ec1bd27)  
![image](https://github.com/DestinyWyche/02_Proj_Rocket-Mortgage_Portfolio_Characteristics/assets/111715383/ba3083a9-1acd-45eb-9540-a3161f4133de)  
![image](https://github.com/DestinyWyche/02_Proj_Rocket-Mortgage_Portfolio_Characteristics/assets/111715383/d5c7ce7c-5a91-4965-b452-bdfda83363c1)
  
 **This complete process can be viewed in file 01**  
  - This enabled me to explore the data and understand what questions it could answer more efficiently. This processed data was then saved as a csv file to be used later in tableau.
  
**Dataset can be viewed in file 02**
  
### Analyzing the data

- To begin analyzing the data, I created **Pivot Tables** to summarize the information. These are critical to being able to gauge information quickly and they also provide a reference to ensure data visualizations are displaying the correct insights
  ![image](https://github.com/DestinyWyche/02_Proj_Rocket-Mortgage_Portfolio_Characteristics/assets/111715383/cbae3e58-dfb5-413f-a255-7a7494ee10be)
  
**Complete tables can be viewed in file 01**  
- Not all stakeholders are familiar with reading tables, so to make the insights more digestible, I created visualizations of each pivot table in **Tableau**. These visualizations were then combined into one dashboard.  

![image](https://github.com/DestinyWyche/02_Proj_Rocket-Mortgage_Portfolio_Characteristics/assets/111715383/db8f2332-1c18-4642-bb7d-02f2093d9e00)
  
  **Source of visualizations can be viewed in file 03**
