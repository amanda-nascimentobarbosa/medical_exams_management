# Medical Exams Management (Controle de Atestado de Saúde Ocupacional)

### Project Category

* Hospital Management, Google Sheets, Looker Studio.

### Business Case

Occupational Health Certificate is a document from Occupational Medicine that aims to attest whether or not the employee is able to perform his/her professional duties for the indicated position. The exam is carried out before, during and at the end of the employment relationship, as part of the Occupational Health Medical Control Program.  The types of exams are Pre-Employment Medical Exam, Periodic Medical Exam, Job Change Health Assessment, Return-to-Duty Medical Exam and Dismissal Medical Exam.

At the hospital, the Occupational Health department is responsible for conducting the exams. Currently, these exams are managed through an Excel spreadsheet, where all information is entered manually without any type of automation, validation, or visualization. And the information is not shared online, which makes it difficult for the entire team to access.

Many exams are overdue due to lack of organization, which has also affected the department's goals. This activity was suspended during the pandemic due to security precautions, which made the situation worse.

### Objectives

The data analyst was requested to organize the data and create a dashboard to monitor the indicators.

- generate a simple solution to organize the information online;
- automate data entry;
- create a dashboard to track the status of exams.

### Projects Limitations

* There was no budget to invest in external solutions, such as hiring software.
* The team members have basic knowledge of how to use Excel, so the project must be easy to maintain.

### Solution

_Tool_
- The spreadsheet was developed using Google Sheets, as the number of records is small, maintenance is simple and now the information is online and available to everyone on the team;
- The dashboard was developed on Looker Studio, also because it is online and has a direct connection with Google Sheets.

_Cleaning_
- The data has been updated and organized, removing duplicates and inconsistencies.

_Automation_
- New columns and formulas for automation were inserted:
    - *Expired Date:* calculates the date taking into account the date of the last exam and the periodicity, semester or annual;
    - *Expired Days:* calculates how many days is left to expire or have already expired;
    - *Status:* addition of the status column that classifies exams as *Valid, Expired, Less than 30 days to expire,* or *Employee dismissed*. Formatting was inserted in this field that assigns colors to each of the statuses.
    - a column was inserted informing whether or not the employee is fit for work.
 
![image](https://github.com/amanda-nascimentobarbosa/medical_exams_management/assets/100388639/9b994220-55fa-4398-a5ba-2b311529eafe)


_Dashboard_
- It was developed in Looker Studio with metrics focused on Exam Expiration Status:
    - total of *Valid, Less than 30 days to expire* and *Expired* exams*;*
    - total number of active employees;
    - bar chart separating the status between the two hospital units;
    - bar graph indicating the number of exams due over the months;
    - table with the number of overdue exams and less than 30 days to expire by department
    - data segmentation by date of expiration, and sector.
 
![image](https://github.com/amanda-nascimentobarbosa/medical_exams_management/assets/100388639/580b898b-26c3-4b5d-af62-772eea277653)

#### You can see the project [here](https://lookerstudio.google.com/reporting/6168a228-b714-47c5-81ab-9ad2489d518c).

### Conclusions

* The automation of the spreadsheet and the creation of the dashboard reduced the time it took to update the data, ensured greater organization, and created a quick view of the information that helps in decision-making.
* Due to the suspension of their performance during the pandemic, it was discovered that the number of expired exams was very high, more than 50% (the data below does not represent the true one). As a result, the department had a subsidy to request the temporary hiring of one more occupational physician who would help with this repressed demand.
