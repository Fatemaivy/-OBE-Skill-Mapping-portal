# -OBE-Skill-Mapping-portal


A Web-based Outcome-Based Education (OBE) Result Management System built with PHP and MySQL. This platform helps educational institutions manage courses, automate student evaluations, calculate academic performances using OBE principles, and export data directly into Excel spreadsheets.

## Key Features
* **Admin Dashboard:** Centralized panel for managing courses, users, and overall system settings.
* **Course Management:** Create, update, and manage academic courses and syllabus structures.
* **OBE Evaluation Engine:** Automate Program Learning Outcomes (PLO) and Course Learning Outcomes (CLO) assessments.
* **Excel Data Processing:** Import student records and export generated grade sheets using PHPExcel.
* **Student Performance Tracking:** Generate visual breakdown of individual and batch-wise academic achievements.

## System Workflow
1. **Setup Courses:** Admin adds courses, credit hours, and mapping parameters.
2. **Input Marks:** Teachers input continuous assessments, midterms, and final exam marks.
3. **OBE Mapping:** System automatically calculates CLO/PLO attainment percentages.
4. **Export Reports:** Results and grade sheets are exported as Excel reports.

## Tech Stack
* **Backend:** PHP
* **Database:** MySQL
* **Libraries:** PHPExcel (Excel handling)
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap

## Prerequisites
* PHP 5.6 or higher
* MySQL Database
* Local Server Environment (XAMPP / WAMP / MAMP)

## Installation & Setup
1. Download or clone this repository into your local server root directory (e.g., `htdocs` for XAMPP).
2. Open **phpMyAdmin** (`http://localhost/phpmyadmin`) and create a new database.
3. Import the provided `.sql` database file into your newly created database.
4. Configure database connection parameters in your project config file if required.
5. Open your browser and navigate to:
   `http://localhost/OBE-Based-Result-Management-System-master/admin/New folder/admin_dashboard.php`

## Authors & Credits
Developed by:
* **Fatema Islam Ivy**
* **Md. Zahidul Islam**
* **Nishat Jahan Nabila**
  
