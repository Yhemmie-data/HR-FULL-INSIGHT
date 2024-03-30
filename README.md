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

### First segment (HOME)

![HOME2](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/2a188e99-5440-41e7-acae-782332f5705f)


The HOME segment of the analysis offers a comprehensive overview of the dataset pertaining to the organization under study, the dataset comprises a total of 1470 employees, with gender distribution indicating 60% are male while the remaining 40% are female. Regarding promotion eligibility, employees whose last promotion occurred more than 10 years ago are identified as candidates due for promotion, constituting 4% of the total workforce. Conversely, the majority (96%) of employees whose last promotion took place within the past decade are categorized as not due for promotion.
Service years distribution reveals that a significant portion of employees (196) have completed 5 years of service, followed closely by 171 employees with 4 years of service and 128 employees with 3 years of service. In contrast, only one employee each has completed service durations of 34 years, 37 years, and 40 years, representing the least prevalent service durations within the dataset. Regarding distance status from the workplace, the analysis indicates that 64% of employees reside very close to their work location, while 16% and 20% report their distance as very far and close, respectively.

### Second segment (ACTION)
![ACTION 3D](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/efe4593c-f7c7-423a-82a5-1c369cb19251)


The second section of the analysis consist of the list of employees who are identified as due for promotion and those slated for retrenchment within the dataset. Specifically, it lists the names of 66 employees deemed eligible for promotion and 177 of those earmarked for retrenchment. It's noteworthy that certain names appear in both lists, indicating individuals who are recommended for compensation in light of their status as both promotion-eligible and retrenchment-eligible employees. This section serves to highlight the individuals undergoing significant career transitions within the organization, facilitating further examination and decision-making processes.

### Third segment (DETAILS)
![details hd](https://github.com/Yhemmie-data/HR-FULL-INSIGHT/assets/162053652/d49557af-a69d-4635-bc06-95a4d9ff50b2)

The final section of the analysis offers a detailed breakdown of the retrenchment and promotion statuses categorized by department, job role, job satisfaction, and job rating. Within the dataset, the Research and Development department emerges with the highest number of employees eligible for both promotion and retrenchment, followed by the Sales and Human Resources departments. This suggests a significant organizational focus on these departments for workforce adjustments.
When examining job roles, it becomes apparent that Managers, Sales Executives, and Research Directors constitute the majority of employees eligible for both promotion and retrenchment. This indicates a potential restructuring or realignment within these pivotal roles across various departments. Regarding job rating, a substantial 85% of the total workforce records low job ratings, while only 15% register high job ratings. This disparity underscores potential areas of concern within job satisfaction and performance levels across the organization. It may necessitate interventions aimed at improving employee morale, engagement, and productivity to mitigate the prevalence of low job ratings.
This detailed breakdown by department, job role, job satisfaction, and job rating provides valuable insights into the distribution of promotion and retrenchment statuses across different organizational dimensions. Such insights are instrumental in informing strategic decision-making processes aimed at optimizing workforce dynamics and organizational performance.

### Recommendations

#### Strategic Workforce Planning:
Given the disparities in promotion and retrenchment across departments and job roles, it's imperative for the organization to engage in strategic workforce planning. This involves aligning workforce needs with business objectives, reallocating resources where necessary, and ensuring the right talent is in the right roles to drive organizational success.

#### Talent Development and Succession Planning: 
With a significant proportion of employees eligible for promotion and retrenchment, investing in talent development and succession planning becomes crucial. Identifying high-potential employees, providing them with opportunities for growth and advancement, and establishing clear pathways for career progression can help retain top talent and mitigate the impact of workforce changes.

#### Performance Management and Job Satisfaction:
Addressing the prevalence of low job ratings and job satisfaction levels is paramount. Implementing robust performance management systems, conducting regular employee feedback sessions, and offering opportunities for professional development and recognition can enhance job satisfaction, boost morale, and improve overall performance levels.

#### Communication and Transparency: 
Transparency regarding promotion and retrenchment processes is essential to maintain employee trust and morale. Communicating openly about the rationale behind workforce decisions, providing avenues for employee feedback and input, and ensuring fairness and equity in decision-making processes can foster a positive organizational culture and mitigate potential resistance to change.

#### Employee Support and Well-being: 
Recognizing that workforce changes can have significant implications for employees, it's important to provide adequate support and resources to those affected. Offering career counseling, skill development programs, and assistance with job 

### Conclusion
The analysis revealed disparities in promotion and retrenchment across departments, job roles, and job satisfaction levels, underscoring the need for strategic workforce planning, talent development, and performance management initiatives.
Moving forward, it is recommended that the organization prioritize strategic workforce planning efforts to align talent with business objectives, invest in talent development and succession planning to retain top performers, and focus on enhancing job satisfaction and performance levels through transparent communication and employee support initiatives.
By addressing these areas proactively, the organization can navigate workforce changes effectively, optimize talent utilization, and foster a positive organizational culture conducive to long-term success and sustainability. Through continued monitoring and adaptation, the organization can remain agile and resilient in the face of evolving workforce dynamics and external challenges.


