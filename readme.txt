# 🦠 Nipah Virus (NiV) Testing Management System

A web-based application designed to manage and streamline the testing, tracking, and reporting of Nipah Virus (NiV) cases. This system enables healthcare staff to efficiently register patients, record test results, monitor case status, and generate reports for authorities.

## 📌 Features

- ✅ Patient registration and test scheduling
- 🧪 NiV test result entry and history tracking
- 📊 Dashboard for test status: positive, negative, pending
- 📁 Report generation in PDF/CSV formats
- 🔍 Search and filter patients by ID, name, or test status
- 🔒 Admin login and role-based access control

## 🛠️ Tech Stack

| Frontend         | Backend         | Database       | Tools & Libraries       |
|------------------|------------------|----------------|--------------------------|
| HTML, CSS, JavaScript | Java (Servlet/JSP) or PHP | MySQL or PostgreSQL | Bootstrap, JDBC, Apache POI (for reports) |

## 🚀 Getting Started

### Prerequisites

- Java JDK / XAMPP / Apache Tomcat (depending on backend)
- MySQL or compatible DB
- IDE like Eclipse / NetBeans / VS Code

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Kavya123k/niv-testing-management.git
   cd niv-testing-management

📂 Folder Structure

niv-testing-management/
├── src/
│   ├── admin/
│   ├── patient/
│   ├── reports/
│   └── db/
├── web/
│   ├── css/
│   ├── js/
│   └── jsp/
├── database/
│   └── niv_management.sql
└── README.md

🔗 [View Project Locally](http://localhost/nipah-tms/nipah-tms/)


How to run the Nipah Virus (Niv) Testing Management Project using PHP and MySQL

1. Download the project zip file

2. Extract the file and copy nipah-tms folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/Html)

4.Open PHPMyAdmin (http://localhost/phpmyadmin)

5. Create a database with the name  nipahtmsdb

6. Import nipahtmsdb.sql file(given inside the zip package in SQL file folder)

7. Run the script http://localhost/nipah-tms

Admin Credential
Username: admin
Password: Test@123
