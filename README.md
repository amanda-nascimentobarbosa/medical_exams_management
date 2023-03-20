# Medical Exams Management (Controle de Atestado de Saúde Ocupacional)

*Disclaimer: This project is similar to another one I developed while working as a resident in Hospital Management. The data used in the analysis are fictitious.*

### Project Category

* Hospital Management, project automation.

### Business Case

Occupational exams are medical exams that aim to evaluate the health of the worker before, during, and at the end of their employment with the company, being part of the Occupational Health Medical Control Program and regulated by NR 07 (brazilian legislation). The types of the exams are Pre-Employment Medical Exam, Periodic Medical Exam, Job Change Health Assessment, Return-to-Duty Medical Exam and Dismissal Medical Exam.

The Occupational Health sector of the hospital used to perform Occupational exams control through an Excel spreadsheet. All information was manually entered without any type of automation or data validation, and there were no quick visualization methods for the information.

This situation resulted in many cases of lack of information and data duplications. In addition to the difficulty of quickly determining how many employees had expired exams.

The lack of exam management caused delays in conducting exams, which impacted the department's goals, as not conducting exams within the appropriate time frame can result in fines and penalties for the organization.

Another problem faced by the team was the workload overload. Spreadsheet updates took a lot of time and delayed the team's work.

During the Covid-19 pandemic, the exams were suspended due to safety concerns, which caused a significant backlog in all demands, in addition to the workload burden on the occupational physician responsible for conducting these exams.

### Projects Limitations

* There was no budget to invest in external solutions, such as hiring software.
* The team had low knowledge of Excel or other planning tools.

### Solution

* The existing Excel spreadsheet was kept, as the team was already familiar with the tool, and the number of records was small and easy to maintain.
* The data has undergone a cleaning and updating process.
* Formulas were added for validation and automatic information generation:
      * Calculation of the due date taking into consideration the date of the last exam and the periodicity (biannual or annual);
      * Calculation of how many days are left until expiration or if it has already expired;
      * Insertion of the *status* column that classifies the exams as valid, expired, less than 30 days to expire or employee dismissed. In this column, a formatting was added that assigns colors to each of the statuses.
      * A column was added informing whether the employee is fit or not for work.
* The developed dashboard contains the main metrics for the sector: the total number of employees, the number of valid exams, those that expire in the next 30 days, and those that have expired. It also shows the number of exams that expire throughout the year, separated by months, providing an overview of the demand for these exams throughout the year. Additionally, there is a summary table with the main data on employees.

### Conclusions

* The automation reduced the time to update the data, better organization of the demands and better integration of the team.
* From the organization of information, it was found that the number of expired exams was very high (more than 50%), due to the suspension of their performance during the beginning of the pandemic. As a result, the sector had a subsidy to request temporary hiring and one more occupational physician who would help with this repressed demand, in addition to the increase in work due to Covid-19.


https://user-images.githubusercontent.com/100388639/225772903-6efcc39d-026b-4c7f-9830-c5d8683b4c8d.mp4

