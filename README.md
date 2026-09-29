# Task Manager (Laravel)
A simple and user-friendly task management system developed using Laravel and MySQL. It allows users to create, organize, update, and track tasks in one dashboard. The system includes features such as task searching, priority filtering, and status tracking to make task management easier and more organized.

Project Code: WST21-PM-2026-SF

Student Name: JENNY BABE C. NUNEZ

Course & Year: BSIT2

Database Used: MySQL

## Overview
This project is a Laravel-based Personal Task Manager created as a mini project. It helps users create, manage, and organize their tasks in one simple system. The application uses the Laravel MVC structure, where routes, controllers, models, and views work together. Task information is stored in a MySQL database, while Laravel handles the main operations of the system. It also allows users to update task statuses, such as moving tasks from Pending to Completed.

## Features
- Add Task: Allows users to create a new task by entering the task title, description, priority, and due date.
- View Tasks: Displays all saved tasks in one place, making it easy to check pending and completed tasks.
- Edit Task: Lets users modify task information whenever they need to make changes or corrections.
- Delete Task: Allows users to remove tasks that are no longer needed from the task list.
- Update Status: Enables users to mark tasks as completed or change them back to pending with one click.

## Setup
1. Start XAMPP
Open the XAMPP Control Panel and start the Apache and MySQL modules.
2. Create the Database
Open phpMyAdmin through http://localhost/phpmyadmin and create a new MySQL database using the same name specified in the .env file.
3. Install Dependencies
Open the project folder in the terminal and run: composer install
4. Create the Environment File
Create a copy of the .env.example file and rename it to .env: cp .env.example .env
5. Generate the Application Key
Run the following command: php artisan key:generate
6. Reset and Create the Database Tables
Run: php artisan migrate:fresh
8. Start the Laravel Server
Run: ph artisan serve
8. Open the System
Open your browser and go to: http://127.0.0.1:8000

Database Reminder:
Make sure the database settings in the .env file match your MySQL/XAMPP configuration, especially the database name, username, password, and port.

## Screenshots
<img width="1908" height="952" alt="image" src="https://github.com/user-attachments/assets/422c425a-63d7-45c2-b5b8-bda95169089f" />
<img width="1904" height="952" alt="image" src="https://github.com/user-attachments/assets/cea8fdf0-738e-476e-a43d-cffbe0846e17" />
<img width="1903" height="941" alt="image" src="https://github.com/user-attachments/assets/a404019d-9b17-4722-af7b-a289efcfa9ed" />
<img width="1904" height="945" alt="image" src="https://github.com/user-attachments/assets/6a228b0c-0a5c-4d67-8f4d-4c8fa66c6cc9" />









