# Examfiy

## Overview  
The Online Examination System is designed to streamline exam management for students and organizations. Students can log in, take exams, view grades, and manage profiles. Instructors and administrators can manage students, courses, and exams, and generate reports.

## Features  
- **For Students**:  
  - Log in and access exams.  
  - View grades and performance.  
  - Manage profile information.  

- **For Instructors/Administrators**:  
  - Add and manage students and courses.  
  - Create and assign exams.  
  - View and analyze student performance.  
  - Generate PDF reports for system data.  

## Technologies Used  
- **Backend**:  
  - C#  
  - ASP.NET MVC Core  
  - Entity Framework Core  
  - SQL Server  
  - Identity Authentication  

- **Frontend**:  
  - HTML, CSS, JavaScript  
  - Bootstrap, jQuery  

- **Design Patterns**:  
  - Repository Pattern  
  - Dependency Injection  

- **Reporting**:  
  - Microsoft Report Builder  

## Development Approach  
- Database-first methodology: Designed the database and reverse-engineered it into models and classes.  
- Utilized Stored Procedures for database operations.  
- Implemented state management for user sessions and system interactions.

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/khloudHisham/Examfiy_MVC_Project.git
   ```
2. Open the project in Visual Studio.  
3. Update the connection string in `appsettings.json` to match your SQL Server configuration.  
4. Run the migrations or ensure the database is set up.  
   ```bash
   Update-Database
   ```
5. Build and run the project.  

## How to Use  
- Navigate to the login page to access the system.  
- Use instructor/admin accounts to manage exams, students, and generate reports.  
- Students can log in to take exams and view their grades.

## Contributing  
Contributions are welcome! Feel free to open issues or submit pull requests.


