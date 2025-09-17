# Hospital Management System (CareCoord)

## About the Project
A full-stack web application for managing hospital operations.  
Patients can register, book appointments online, and view their medical history.  
Doctors, nurses, and administrators each have dedicated dashboards to manage data efficiently.
Originally based on a college project, then customized and documented by Ibrahim Al-Hassan

## Technologies
- **Front-End:** HTML, CSS, JavaScript, Bootstrap  
- **Back-End:** C#, ASP.NET Core 7 (MVC Pattern), MS SQL Server  

## Features
- Patient registration & login  
- Online appointment booking with email confirmation  
- Admin panel to manage doctors, nurses, departments, and appointments  
- Doctors can create prescriptions linked to patients  
- Pharmacy/Nurse module for dispensing medicine  
- Database diagram and screenshots included  

## Setup
1. Clone this repository  
2. Install [.NET 7.0](https://dotnet.microsoft.com/en-us/download)  
3. Restore the database from the provided `.bak` file  
4. Update the connection string in:  
   - `HMSproject/appsettings.json`  
   - `HMSproject/Controllers/Nurse_aymanController.cs`  
   - `HMSproject/Areas/Identity/Pages/Account/Manage/DeletePersonalData.cshtml.cs`  

## Screenshots
![Home](https://github.com/gong70631-star/Hospital-Management-Ibrahim/raw/main/HMSproject/wwwroot/images/screenShot/home.png)
![Admin Panel](https://github.com/gong70631-star/Hospital-Management-Ibrahim/raw/main/HMSproject/wwwroot/images/screenShot/admin.png)
![Doctor Dashboard](https://github.com/gong70631-star/Hospital-Management-Ibrahim/raw/main/HMSproject/wwwroot/images/screenShot/doctor.png)
![Nurse Dashboard](https://github.com/gong70631-star/Hospital-Management-Ibrahim/raw/main/HMSproject/wwwroot/images/screenShot/nurse.png)

## Author
**Ibrahim Al-Hassan**  
📧 gong70631@gmail.com  
GitHub: https://github.com/gong70631-star
