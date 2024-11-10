Employee Management System

A comprehensive Employee Management System (EMS) built using MySQL, JavaScript, and HTML. This system enables administrators to manage employee information, track job details, and store personnel records in a centralized, easy-to-use interface.

https://github.com/user-attachments/assets/7c91176e-0a0d-4ff6-afb0-e51cc51e5f8b


Features
Add Employees: Allows adding employee records with full details like name, email, address, and salary.
Edit and Delete: Edit employee data and remove entries as needed.
Filter and Search: Search employees by name, department, or role.
Role-Based Access Control: Permissions for admin and standard users.
Responsive Design: Works well on different devices.

Getting Started

Prerequisites

Before running the project, ensure you have the following installed:

Node.js and npm
MySQL server


Installation

Clone the Repository:

bash
Copy code
git clone https://github.com/poison01022/EMPLOYEE-MANAGEMENT---SYSTEM.git
cd EMPLOYEE-MANAGEMENT---SYSTEM



Install Backend Dependencies:

bash
Copy code
cd backend
npm install




Set Up the Database:

Start your MySQL server

Create a new database for this project:

sql
Copy code
CREATE DATABASE employee_management;
Import the provided SQL file:
bash
Copy code
mysql -u [username] -p employee_management < database/schema.sql
Update your config.json or .env file with database credentials.



Run the Backend Server:

bash
Copy code
npm start
Run the Frontend (optional):

Open index.html in a web browser to load the frontend interface.
Usage
Adding an Employee
To add an employee, fill in the required fields on the "Add Employee" form and submit.

Editing an Employee
Locate the employee using the search or filter options.
Click "Edit" next to the employee’s name.
Update the necessary details and save.
Deleting an Employee




Directory Structure
Here's how the project is organized:

plaintext
Copy code
Employee-Management-System/
├── backend/
│   ├── config/                 # Configuration files (e.g., DB credentials)
│   ├── controllers/            # Business logic and controllers
│   ├── models/                 # Database models
│   ├── routes/                 # Express routes for API
│   ├── server.js               # Main server file
│   └── .env                    # Environment variables
│
├── frontend/
│   ├── index.html              # Main HTML file for UI
│   ├── style.css               # CSS file for styling
│   └── script.js               # JavaScript for frontend logic
│
└── README.md                   # Project README













Click "Delete" next to the employee's record.
Confirm to permanently remove the employee from the database.
