# HR Attrition using Power BI

My recent data project on HR attrition using Power BI focused on understanding and mitigating employee turnover in organizations. 

By analyzing factors such as job involvement, job satisfaction, relationship satisfaction, and environment satisfaction, I gained valuable insights into the causes of attrition.

I gathered the HR attrition dataset from Kaggle, a platform that provides datasets for data enthusiasts. 

After cleaning and organizing the data, I created various measures and built a data model to establish relationships between tables. Using Power BI's visualization capabilities, I presented the analysis findings through charts and graphs.

The analysis revealed that the attrition rate was **16.12%**, with the highest number of employees leaving falling between **31-40** years of age. 

Male employees constituted the majority of attrition cases. 

Employees with less than five years of experience and those in entry-level positions had higher attrition rates. 

Additionally, job involvement, job satisfaction, and relationship satisfaction were identified as significant contributors to attrition.


Here is the link to the dataset. [HR Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)


## Overview of the Dataset
![Data Overview](https://github.com/thelukmonkazeem/hrAttrition/blob/main/Data%20Overview.PNG)


## Data Cleaning

During the data cleaning phase, I executed the following actions to ensure dataset cleanliness and accuracy:

- I renamed the attrition column to status and transformed the values from Yes or No to turnover and retention, respectively.
- I changed the education values from a scale of 1-5 to a more descriptive range from SSCE to PhD.
- I renamed the employeeNumber column to employeeID for improved clarity.
- I modified the values of environment satisfaction, job involvement, job satisfaction, and relationship satisfaction from 1-4 to a more intuitive scale ranging from Low to Very High.

## Data Model
The data model showcases the connections between the created tables. The Hrmaster table serves as the main focus of analysis, known as the fact table, while other tables like employee and salary function as supporting dimension tables.

In Power BI, fact and dimension tables are fundamental components. The fact table contains the core data that is the primary focus of analysis, while dimension tables provide additional descriptive information about various aspects of the analysis.


To streamline and simplify the data analysis process, I organized the data into distinct tables. Each table serves a specific purpose, enhancing the clarity and ease of analysis.

The **Employee** table holds valuable information about employees, including details such as age, department, and more.

The **Salary** table focuses on employee compensation, resembling a payroll database.

The **HrMetric** table encompasses essential columns such as job involvement, job satisfaction, relationship satisfaction, and environment satisfaction, providing valuable insights into employee metrics.

The **JobInfo** table revolves around job-related information, offering comprehensive data related to various job aspects.

The **Performance** table concentrates on employee performance, capturing crucial performance-related data.

Finally, the HrMaster table acts as the central repository, serving as the master table that integrates and connects the other tables for comprehensive analysis.

![Data Model](https://github.com/thelukmonkazeem/hrAttrition/blob/main/DataModel.PNG)


## Measures
Below are the snapshots of some of the measures that I created.

**Age Group:** The age group measure creates a category for employee's age.
![Age Group](https://github.com/thelukmonkazeem/hrAttrition/blob/main/ageGroup.PNG)

**Attrition Rate:** This measure calculate the attriiton rate of the employees.
![Attrition rate](https://github.com/thelukmonkazeem/hrAttrition/blob/main/attrition.PNG)

## Dashboard Snapshots
### HR Analytics
![HR Analytics](https://github.com/thelukmonkazeem/hrAttrition/blob/main/1.jpg)

### HR Performance
![HR Performance](https://github.com/thelukmonkazeem/hrAttrition/blob/main/2.jpg)

### HR Attrition Analysis
![HR Attrition Analysis](https://github.com/thelukmonkazeem/hrAttrition/blob/main/3.jpg)

You can interact with the full dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiMDU0YmY2ZDUtYTc5ZS00ODFlLWJmY2UtZDU0NjViMWJkMDE4IiwidCI6IjcxNDg1YWRiLTNkOTktNDg0OS05MjFhLTlhZWQ5MTJkNWYzZSJ9).
