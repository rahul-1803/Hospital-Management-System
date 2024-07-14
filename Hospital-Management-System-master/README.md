# Hospital Management System
Hospital Management System using MySQL, PHP, and Bootstrap

## Need to work on:

1. Ability for doctors to accept appointments and acknowledge patients that their appointments have been approved.
2. Prevent users from registering with an already registered email ID.
3. Encrypt passwords and hide the password field in the admin panel.
4. Implement pagination for all list views across the application.
5. Fix bug where bill payment receipt contains multiple records if a patient has multiple visits with the same doctor.
6. Add more fields in the prescription statement for specificity.
7. Add more details on payments, such as the date of payment and amount paid.
8. Implement an export button in the admin module to export all details to an Excel sheet.

## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with the latest version

## Languages and Technologies Used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. PHP
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

## Steps to Run the Project on Your Machine
1. Download and install XAMPP on your machine.
2. Clone or download the repository.
3. Extract all files and move them to the 'htdocs' folder of your XAMPP directory.
4. Start Apache and MySQL in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'.
6. In phpmyadmin, create a new database named 'myhmsdb'.
7. Import the 'myhmsdb.sql' file into your newly created database.
8. Open a new tab and type 'localhost/foldername' in your browser's URL bar.
9. You're all set!

### Software Used
- XAMPP was installed on an Ubuntu 19.04 machine, and Apache2 Server and MySQL were initialized. Files were built inside opt/lampp/htdocs/myhmsp.
- Sublime Text 3.2 was used as the text editor.
- Google Chrome Version 77.0.3865.90 was used to run the project (localhost/myhmsp was used as the URL).

### Starting Apache and MySQL in XAMPP:
The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.

<p align="center"><img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png"></p>

## Getting into the Project:
The Hospital Management System in PHP and MySQL includes a ‘Home’ page where patients, doctors, and administrators can log in to their accounts by toggling the tabs accordingly. Below are descriptions of the main modules and features.

### Patient Module:
Patients can create their account, book appointments, and view their appointment history. The registration page asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password, and select their gender.

![image](https://user-images.githubusercontent.com/36665975/66570027-5b393200-eb8a-11e9-9e97-088630b5e583.png)

Upon registration, patients are redirected to their Dashboard, where they can book appointments and view their appointment history.

![image](https://user-images.githubusercontent.com/36665975/66570123-8c196700-eb8a-11e9-845f-ea02013f1d5c.png)

### Doctor Module:
Doctors can log in to their accounts (registration is handled by the admin). They can view their appointments, search for patients by contact number, and manage their schedules.

![image](https://user-images.githubusercontent.com/36665975/66570704-be779400-eb8b-11e9-92ae-21d8e0e4aba4.png)

### Admin Module:
The admin can view lists of patients, doctors, and appointments, add new doctors, and view user feedback or queries. The admin dashboard includes options to manage the system efficiently.

![image](https://user-images.githubusercontent.com/36665975/66570841-03032f80-eb8c-11e9-9cfc-62b6b869c918.png)

## Updates

### 1. Cancel Appointments
Patients and doctors can delete their appointments, with changes reflected in both the patient's and doctor's dashboards.

![image](https://user-images.githubusercontent.com/36665975/75169873-47642600-574f-11ea-8ca4-420b0dfd20c3.png)

### 2. Remove Doctors by Admin
Admins can delete doctors from the system, providing more control over the hospital management.

![image](https://user-images.githubusercontent.com/36665975/75170650-6d3dfa80-5750-11ea-8f05-455c7d704217.png)