````markdown
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
- Bootstrap
- SQLite Database

---

# Project Structure

```bash
Online-Examination-System/
│
├── exam/
├── student/
├── teacher/
├── templates/
├── static/
├── screenshots/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

---

# Screenshots

## Home Page

![Home Page](screenshots/homepage.png)

## Admin Dashboard

![Admin Dashboard](screenshots/admin-dashboard.png)

## Student Dashboard

![Student Dashboard](screenshots/student-dashboard.png)

## Online Examination Page

![Exam Page](screenshots/exam-page.png)

## Result Page

![Result Page](screenshots/result-page.png)

---

# Installation Guide

## Step 1: Clone the Repository

```bash
git clone https://github.com/manasi2654/OnlineExaminationSystem.git
cd OnlineExaminationSystem
```

## Step 2: Create Virtual Environment

```bash
python -m venv venv
```

## Step 3: Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

## Step 4: Install Required Packages

```bash
pip install -r requirements.txt
```

## Step 5: Make Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

## Step 6: Create Admin/Superuser

```bash
python manage.py createsuperuser
```

## Step 7: Run the Application

```bash
python manage.py runserver
```



# Contact Us Page Configuration

Update email credentials in `settings.py`:

```python
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-password'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
```

---

