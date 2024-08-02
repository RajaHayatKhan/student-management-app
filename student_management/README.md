# Student Management App

A Django web application for managing student records. This app includes features for adding, editing, and viewing student details, along with user authentication.

## Features

- **CRUD Operations:** Create, Read, Update, and Delete student records.
- **User Authentication:** User registration, login, and logout.
- **Admin Controls:** Only admins can add or delete students.

## Prerequisites

- Python 3.8 or later
- Django 5.x
- A database system (SQLite is used by default)

## Setup Instructions

1. **Clone the Repository**

   ```sh
   git clone https://github.com/Rajahayatkhan/student-management-app.git
   cd student-management-app
   Create a Virtual Environment

Copy code
python -m venv env
Activate the Virtual Environment

On Windows:
sh
Copy code
.\env\Scripts\activate
On macOS/Linux:
sh
Copy code
source env/bin/activate
Install Dependencies

sh
Copy code
pip install -r requirements.txt
Apply Database Migrations

sh
Copy code
python manage.py migrate
Create a Superuser

sh
Copy code
python manage.py createsuperuser
Follow the prompts to create an admin user.

Run the Development Server

sh
Copy code
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to view the application.
Usage
Register a new user: Go to /register/ to create a new account.
Log in: Go to /login/ to log in.
Add a student: After logging in, go to /add/ to add a new student.
Edit a student: Click "Edit" next to a student's name to modify their details.
Delete a student: Click "Delete" next to a student's name (only visible to admin users).
View student details: Click on a student's name to view their details.