# Medical Exams Management (Controle de Atestado de Saúde Ocupacional)

*Disclaimer: This project is similar to another one I developed while working as a resident in Hospital Management. The data used in the analysis are fictitious.*

### Project Category

* Hospital Management, project automation, Excel.

### Business Case

Occupational exams are medical exams that aim to evaluate the health of the worker before, during, and at the end of their employment with the company, being part of the Occupational Health Medical Control Program and regulated by NR 07 (brazilian legislation). The types of the exams are Pre-Employment Medical Exam, Periodic Medical Exam, Job Change Health Assessment, Return-to-Duty Medical Exam and Dismissal Medical Exam.

The Occupational Health departament of the hospital used to perform occupational exams control through an Excel spreadsheet. All information was manually entered without any type of automation or data validation, and there were no quick visualization methods for the information.

This situation resulted in many cases of lack of information and data duplications. Also, it was difficult to quickly determine how many employees had expired exams and how many of them were about to expire in the following months.

The lack of management caused delays in conducting the checkups, which impacted the department's goals. And by not conducting the exams within the appropriate time frame, it can result in fines and penalties for the organization.

Also, because of the lack of automation, the spreadsheet updates took a lot of time and delayed the team's work.

During the COVID-19 pandemic, the exams were suspended due to safety concerns, which caused a significant backlog in all demands. especially for the occupational physician in charge of these examinations.

### Projects Limitations

* There was no budget to invest in external solutions, such as hiring software.

### Solution

* The existing Excel spreadsheet was kept, as the team was already familiar with the tool and the number of records was small and easy to maintain.
* The data has undergone a cleaning and updating process.

* Changes in the spreadsheet:
     * Formulas were included for automatic information generation and validation:
          * Calculation of the due date, taking into consideration the date of the last exam and the periodicity (biannual or annual);
          * Calculation of how many days are left until the exam expiration or if it has already expired;
          * Addition of the *status* column that classifies the exams as: *valid*, *expired*, *less than 30 days to expire* or *employee dismissed*. In this column, a color format was added, assigning different colors to each of the statuses.
          * The status of the employee's suitability for employment was indicated in a new column.

* Dashboard
     * The dashboard includes the key statistics, including the total number of employees, the number of valid tests, exams that expire in the next 30 days, and exams that have already expired. 
     * A summary of the demand for these tests over the course of the year is provided by the number of exams that expire during the year, broken down by months. 
     * A summary table with the key information on the staff is also included.
     * All of this can be filtered by branches and departments.


### Conclusions

* The automation reduced the time to update the data, better organization of the demands and better integration of the team.
* Due to the suspension of their performance during the pandemic, it was discovered that the number of expired exams was very high, more than 50% (the data below does not represent the true one). As a result, the department had a subsidy to request the temporary hiring of one more occupational physician who would help with this repressed demand.

### Dashboard

https://user-images.githubusercontent.com/100388639/228375076-0e0ff04a-3b84-46f6-a5b1-7a2238307860.mp4


#### You can see the project [here](https://github.com/amanda-nascimentobarbosa/medical_exams_management/blob/main/Medical%20Exams%20Management.xlsm).

