# SD-3101 ATTENDANCE TRACKING SYSTEM

   This PHP attendance system project is designed to manage student attendance and records effectively.
It features three main sections: Admin Panel, Student Panel, and Teacher's Panel. The admin can create
users and manage data, while teachers can track attendance for their subjects, and students can view
their attendance records.


#
![Screenshot (1308)](https://user-images.githubusercontent.com/36708000/173136998-4de6eccc-377f-419e-83b6-e767503bbb5d.png)
#
![Screenshot (1309)](https://user-images.githubusercontent.com/36708000/173137041-69d68213-077d-4362-bd4e-cfba5a6b2202.png)
#
![Screenshot (1313)](https://user-images.githubusercontent.com/36708000/173137057-5aad5420-7689-4d5e-aae0-df796154e993.png)
#
![Screenshot (1316)](https://user-images.githubusercontent.com/36708000/173137075-81d7b66e-a5cc-4228-ab14-cecc465701d7.png)



## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
   Managing attendance in schools, colleges, or universities is very important. Traditional ways of tracking attendance
by hand can take a lot of time, lead to mistakes, and be hard to keep up with. This PHP Attendance System helps solve these
problems by making attendance management easier. It is a digital platform that lets administrators, teachers, and students
work with attendance data in a simple and easy way. The system makes tracking attendance, managing data, and creating reports
easier, ensuring accuracy and saving time for both teachers and students.

   The system has different user roles like Admin, Teacher, and Student. This makes sure each user can use specific features
that match their role. Administrators can manage the whole process, teachers can track and update attendance, and students can
easily check their own attendance, making the records more organized and easier to manage.
 

## Project Overview
   This PHP Attendance System is made for schools, colleges, and universities. It gives a reliable and easy way to manage and
track student attendance. The system has three main sections: an Admin Panel, a Teacher Panel, and a Student Panel. Each section
is designed to meet the needs of its users.

   In the Admin Panel, the administrator can manage students, classes, classrooms, and teachers, and can track attendance for
the whole institution. In the Teacher Panel, teachers can track attendance for their own subjects and view class information. In
the Student Panel, students can check their own attendance history, helping them take more responsibility. This project replaces
the old paper-based attendance system with a digital solution that reduces mistakes, organizes data better, and allows faster
reporting. It helps keep attendance records accurate and always up-to-date.


## Objectives
Develop a solution for efficient attendance tracking.
Implement user roles and permissions.
Test and validate the system for usability and reliability.


## Features
List the main features of the project:
 Feature 1: Admin Side
 	 Brief description: The admin has access to a dashboard that displays comprehensive
information about students, classes, classrooms, the total number of students, class teachers,
and session terms. In short, the admin manages all of these, from organizing students and
classes to monitoring teachers and session terms.
   

 Feature 2: Teacher Side
	Brief description: Teachers have their own dashboard, which shows students, classes,
 classrooms, and the total number of their students. However, teachers are limited to managing
 only their own students and classes.


 

## Technologies Used
PHP
Frameworks/Libraries: Bootstrap for UI
Databases: MySQL
Other Tools: Git for version control



## Setup and Installation
Step-by-step instructions for setting up the project locally.

 Step 1: Installation of Git CLI.
	- The initial step in this process involves ensuring the installation of
the Git Command Line Interface (CLI) on the computing device that will be
employed. This installation is a prerequisite, as the Git CLI is an essential
tool required for the entirety of this procedure. The absence of this tool on the
machine would impede any further progression in the development process.
Additionally, the Git CLI will be utilized for the critical task of cloning the
relevant repository.


 Step 2: Copying and cloning the repository.
	- Upon successful installation of the Git CLI, the next step involves
identifying a repository that closely mirrors the intended application system,
specifically an "Attendance Checker Application System." This repository must
then be cloned into a designated file location within the local hard drive of the
computing device being used.


 Step 3: Setup of the repository in XAMPP/PHPMyAdmin.
	- Following the completion of the cloning process, the subsequent phase
entails executing and testing the cloned repository. This step is crucial in
determining the functionality of all included components. Moreover, it is
necessary to evaluate the compatibility of the programming languages and
technologies employed within the repository against those available in our
development environment. This assessment is critical in determining the relevance
of our prior knowledge and will streamline the subsequent setup process.


 Step 4: Testing Phase.
	- The testing phase serves as a pivotal point in ascertaining whether the
acquired repository is appropriate for the development of the intended
application system and whether it aligns with the theoretical and practical
knowledge acquired throughout our studies. For instance, it is imperative to
assess our familiarity with the programming languages and tools utilized in the
repository. This evaluation extends to any Integrated Development Environments
(IDEs) or supplementary applications that may be required.


 Final Step: Updating the Tracker to monitor the progress.
	- The concluding step involves updating the project tracker to document
and monitor our progress throughout the development process. This practice
ensures systematic tracking and facilitates effective project management.



1. **Clone the repository:**
   ```bash
   git clone https://github.com/dev-mhrony/Student-Attendance-System01.git
   ```
2. **Install dependencies:**
	
3. **Configure environment variables (if any)**: Provide instructions for setting up .env files or any other required configurations.
   ```bash
   git clone https://github.com/dev-mhrony/Student-Attendance-System01.git
   ```
4. **Run the project:**
   - For web projects:
   ```bash
  php -S localhost:8000

   ```

## Usage Instructions

Access the application:
- After setup, open your browser and go to [http://localhost:8000.](http://localhost/Student-Attendance-System01)
Log in using the provided credentials.


**Admin Login Details**
Email : admin@mail.com
Password: Password@123

**Teacher Login Details** 
Email : teacher@mail.com
Password: pass123




## Project Structure
Explain the structure of the project directory. Example:
```bash

.
├── Admin
├── ClassTeacher
├── DATABASE FILE
├── Includes
├── css
├── font
├── img
├── js
├── scripts
├── scss
├── vendor
├── .gitattributes
├── .gitignore
├── README.md
├── classTeacherLogin.php
├── forgotPassword.php
└── index.php
```

## Contributors

List all the team members involved in the project. Include their roles and responsibilities:

- **Vince Ivan Monzales**: Lead Developer, Backend Developer
- **Hana C. Morales**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline

Outline the project timeline, including milestones or deliverables. Example:

- **Week 1-2**: Research and project planning.
	- Feature: Dockerize Project
 	- Complettion Date: 27/10/2024	
- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.
- Added basic functionality for [Feature 1], [Feature 2], and [Feature 3].

### [Version 1.1.0] - 2024-09-14
- Improved user interface for [Feature 1].
- Fixed bugs related to [Feature 2].
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for [Feature 4].
- Refactored codebase for better performance.
- Added unit tests for [Feature 3] and [Feature 4].


## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from [Original Project Name](https://github.com/username/original-repo), created by [dev-mhrony]. You can view the original repository [here](https://github.com/username/original-repo).

## License

Specify the project's license. For starters, adapt the license of the original repository.
