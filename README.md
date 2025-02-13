# Data Gathering & Warehousing 
## DSSA-5102 - Spring 2025
_Data Science and Strategic Analytics Graduate Program_ - [Stockton University](https://www.stockton.edu/)

### Languages & Environment:
- Python, SQL, Anaconda Navigator, Jupyter Notebook, Github, Spyder

### Assignments:
- Assignment #1 - Locating a Dataset
    - Importing data and initial dataset exploration (Master dataset not available on repository). 
- Assignment #2 - Cleaning our Dataset
    - Preparing our dataset for our future class database (Master dataset not available on repository).
- Assignment #3 - Metadata
    - Creating a metadata file with all necessary components

### Student Repositories:
### Indepth Information for Dataset2 "AH Provisional Diabestes Death Count for 2020" dataset
- Where is the data from:- CDC.gov
- How was it collected:- The data originates from death certificates submitted to vital statistics offices across the United States. Each certificate includes information on the causes of death, which are coded according to the International Classification of Diseases, Tenth Revision (ICD-10). For this dataset, deaths where diabetes is listed as the underlying cause are identified using ICD-10 codes E10–E14.
- How was it extracted:- While the specific extraction and cleaning processes are not detailed in the available documentation, it is standard practice for NCHS to extract relevant data from death certificates and process it to ensure accuracy and consistency. This typically involves validating ICD-10 codes, standardizing data formats, and checking for inconsistencies or errors.
- WHat program was used to clean the data:- I 
- What are the units of the numeric data:- The primary numeric data in this dataset represents the count of deaths attributed to diabetes as the underlying cause. These counts are typically presented as whole numbers.
- What were the formulas used in column creation?​
The dataset primarily consists of straightforward counts of deaths. If rates or percentages are included, they are usually calculated using standard epidemiological formulas, such as:

Mortality Rate: (Number of deaths due to diabetes / Total population) × 100,000
- How is the data validated to ensure consistency?​
NCHS employs rigorous data validation procedures to ensure the consistency and reliability of their datasets. This includes cross-referencing data entries, validating ICD-10 coding accuracy, and implementing quality control measures throughout the data processing pipeline.
- What are the definitions for the column names? Include all columns in your dataset.​
Data as of,Date_Of_Death_Year,Date_Of_Death_Month, Age Group, Sex, COVID19(Deaths with COVID-19 (U071) as underlying or contributing cause), Diabetes.uc(Deaths with diabetes (E10–E14) as underlying causec), Diabetes.mc(Deaths with diabetes (E10–E14) as underlying or contributing cause), C19PlusDiabetes(Deaths with COVID-19 (U071) and diabetes (E10–E14)),C19PlusHypertensiveDiseases(Deaths with COVID-19 (U071) and hypertensive disease (I10–I15)), C19PlusMajorCardiovascularDiseases(Deaths with COVID-19 (U071) and major cardiovascular diseases (I00–I78)), C19PlusHypertensiveDiseasesAndMCVD(Deaths with COVID-19 (U071), hypertensive disease (I10–I15), and major cardiovascular diseases (I00–I78)), C19PlusChronicLowerRespiratoryDisease(Deaths with COVID-19 (U071) and chronic lower respiratory disease (J40–J47)), C19PlusKidneyDisease(Deaths with COVID-19 (U071) and kidney disease (N00–N07, N17–N19, and N25–N27)), C19PlusChronicLiverDiseaseAndCirrhosis(Deaths with COVID-19 (U071) and chronic liver disease and cirrhosis (K70, K73–K74)) 

- If there are set variable options in your dataset, what are thier definitions? ​
Age Group: Categories such as "0-4 years," "5-14 years," "15-24 years," etc.
Sex: Typically "Male" or "Female."
Race/Ethnicity: Categories such as "White," "Black or African American," "Hispanic or Latino," etc.
- What are the regulations to using the data?
The dataset is publicly available and can be used for research, analysis, and educational purposes. Users should adhere to the CDC's data use policies, which include:Properly citing the source of the data,
Not using the data to identify individuals,Complying with any additional terms specified by the CDC.
