# Hospital management system
Build hospital management system using Laravel and bootstrap
 - Source Code    :  https://github.com/atifali-pm/hospital-management-system

## Run it Locally
```
$ git clone git@github.com:atifali-pm/hospital-management-system.git
$ cd hospital-management-system/
$ composer update –no-scripts
$ cp .env.example .env and uppdate DB configurations in .env file
$ php artisan migrate
$ php artisan db:seed (Insert test data)
$ php artisan serve (Finally run locally and check on: http://127.0.0.1:8000/)
```

## Features
1. Manage Departments
   1. List departments
   2. Add and edit departments
   3. Delete departments

![alt text](https://github.com/atifali-pm/hospital-management-system/blob/main/public/readme_images/Screenshot-2023-01-22-20-32-10.png)

2. Manage Doctors
    1. List doctors
    2. Add and edit doctors in a department
    3. Delete doctor
 
![alt text](https://github.com/atifali-pm/hospital-management-system/blob/main/public/readme_images/Screenshot-2023-01-22-20-35-03.png)

2. Manage Human resources (Nurses, Pharmacist, Laboratorists, Receptionists and Accountants)
    1. List human resources
    2. Scope user_type and add or edit human resources
    3. Delete human resources

![alt text](https://github.com/atifali-pm/hospital-management-system/blob/main/public/readme_images/Screenshot-2023-01-22-21-00-49.png)

3. More features:
   1. Appointments: Appointments can be managed in the application using the doctor’s and patients’ IDs. 
   2. Registration. 
   3. Check-in and check-out procedures for patients. 
   4. Automation in the laboratory.
   5. Manage Schedule
   6. Manage Pharmacy.
   7. Keeping track of patients’ records.
   8. Managing Financial
   9. Keeping track of employees.
   10. Managing Labs
   11. Payroll System for Employees 
   12. Manage Prescriptions 
   13. Consultant Doctor 
   14. Manage Beds
 
