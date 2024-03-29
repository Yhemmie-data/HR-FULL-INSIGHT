# HR FULL INSIGHT ANALYSIS

This report provides a comprehensive overview of all employees within the organization as compiled by the Human Resources department. It encompasses demographic details of each employee, including their respective departments, educational background, years of service, job level, job satisfaction, promotion status, distance status, performance rating, among others. These data points serve as the basis for assessing whether an employee is eligible for promotion, ineligible for promotion, or subject to retrenchment.

### INTRODUCTION

This report presents detailed data collection and analysis, providing insights into each employee's professional path. By examining demographic information such as departmental affiliations, educational backgrounds, tenure of service, job levels, job satisfaction levels, promotion statuses, distance statuses, and performance ratings, we aim to outline a strategic plan for talent management and organizational optimization. Also this report serves as both a diagnostic tool for current workforce dynamics and a guide for informed decision-making regarding employee development and organizational restructuring. By synthesizing demographic attributes and performance metrics, we seek to empower stakeholders with actionable insights to navigate the delicate balance between talent optimization and financial stewardship.
The primary objectives of this assessment are twofold: to acknowledge and reward employees whose contributions align with organizational goals, promoting a culture of meritocracy and career advancement, and to effectively manage workforce dynamics while ensuring prudent resource allocation and organizational sustainability amidst financial constraints.

### DATA SET DESCRIPTION
The dataset utilized for this analysis was sourced from Youtube tutorial which was already cleaned and it used for analysis after undergoing several transformations to ensure its compatibility and suitability. 

The link to the dataset : [ https://drive.google.com/file/d/1h4bv...]

### Extract, Transform and Load (ETL) Proces

The extraction of the dataset was carried out using Power Query to facilitate efficient data transformation and preparation. The dataset contains information for all employees within the organization, comprising 35 columns and 1470 rows. This indicates that the total number of employees in the organization is 1470, with each employee's information occupying one row in the dataset.

![HR NEW 1](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/39bb1431-cd72-468c-8733-396e6d1b3e3b)


The data was loaded into Power BI in CSV (Comma-Separated Values) format, a widely used file format for storing tabular data. Power BI seamlessly integrates with CSV files, allowing for easy importation and subsequent analysis of the dataset.


![HR NEW 2](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/3ee8af9c-11b7-4cda-96de-0a1512e64a60)


By utilizing Power Query's functionality to handle delimiters, each piece of information previously separated by tabs was allocated to its respective column. This transformation ensured that the dataset was properly structured and ready for further analysis, enhancing the efficiency and accuracy of subsequent data exploration and visualization tasks within Power BI.


![DELIMITER](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/d826c6a3-ac35-4324-bd10-2e9b1f473d77)



### Exploratory Data Analysis : 
An initial exploratory analysis was undertaken using Power BI to gain a comprehensive understanding of the dataset. This analysis is organized into distinct sections aimed at providing thorough insights. The first part of the analysis focuses on several key variables: job level, service year, distance status, and promotion status. This segmentation aids in dissecting the dataset and comprehending the relationships between these variables. The second visualization, labelled "Action," show the names of employees earmarked for promotion as well as those slated for retrenchment. This section provides a clear overview of the impending workforce changes.
Moving on, the third visualization, referred to as "Details," presents various bar graphs depicting the distribution of promotions and retrenchments across different organizational dimensions. These dimensions include departmental affiliations, job roles, job satisfaction levels, and job ratings. This detailed breakdown facilitates a nuanced understanding of how these factors interplay in the decision-making process regarding promotions and retrenchments within the dataset.

### Analysis / Key finding

![HOME2](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/2a188e99-5440-41e7-acae-782332f5705f)


The HOME segment of the analysis offers a comprehensive overview of the dataset pertaining to the organization under study, the dataset comprises a total of 1470 employees, with gender distribution indicating 60% are male while the remaining 40% are female. Regarding promotion eligibility, employees whose last promotion occurred more than 10 years ago are identified as candidates due for promotion, constituting 4% of the total workforce. Conversely, the majority (96%) of employees whose last promotion took place within the past decade are categorized as not due for promotion.
Service years distribution reveals that a significant portion of employees (196) have completed 5 years of service, followed closely by 171 employees with 4 years of service and 128 employees with 3 years of service. In contrast, only one employee each has completed service durations of 34 years, 37 years, and 40 years, representing the least prevalent service durations within the dataset. Regarding distance status from the workplace, the analysis indicates that 64% of employees reside very close to their work location, while 16% and 20% report their distance as very far and close, respectively.










