# Online Examination System using Django Framework

The Online Examination System is a web-based application developed using the Django framework. This system helps automate the examination process by allowing administrators to manage exams, students, questions, and results efficiently. Students can log in, attend exams online, and view their results instantly.

---

# Features

## Admin Module
- Admin Login and Dashboard
- Manage Students and Teachers
- Add, Update, and Delete Exams
- Manage Subjects and Questions
- View Student Results
- Monitor Examination Activities

## Student Module
- Student Registration and Login
- View Available Exams
- Attend Online Exams
- Automatic Result Generation
- View Scores and Performance

## Examination Features
- Multiple Choice Questions (MCQ)
- Timer-Based Examination
- Instant Result Calculation
- Secure Authentication System

---

# Technologies Used

- Python
- Django Framework
- HTML5
- CSS3
- SQLite Database

---

# Project Structure

```bash
Online-Examination-System/
│
├── exam/
├── templates/
├── static/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

Installation Guide
Step 1: Clone the Repository
git clone <repository-url>
cd Online-Examination-System


Step 2: Install Required Packages
pip install -r requirements.txt


Step 3: Make Database Migrations
python manage.py makemigrations
python manage.py migrate


Step 4: Create Admin/Superuser
python manage.py createsuperuser

Enter username, email, and password to create the admin account.

Step 5: Run the Application
python manage.py runserver

Now open the browser and visit:

http://127.0.0.1:8000/
Admin Login

After creating the superuser account, log in using:

http://127.0.0.1:8000/admin
Contact Us Page Configuration

To enable the Contact Us email functionality, update your email credentials in the settings.py file.

Example:

EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-password'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
Default Database

The project uses SQLite as the default database.

Database file:

db.sqlite3
Screenshots
Home Page
Admin Dashboard
Student Dashboard
Online Examination Page
Result Page


