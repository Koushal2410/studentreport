# # Student Report Management System

## Overview

The Student Report Management System is a web-based application developed using Django and REST APIs to manage student records efficiently. The system allows users to add, view, update, and delete student information through a simple and user-friendly interface.

This project helps educational institutions maintain student data digitally, reducing manual record management and improving accessibility.

---

## Features

* Add new student records
* View student details
* Update student information
* Delete student records
* REST API integration
* Responsive user interface
* Secure data management using Django backend

---

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Django
* Django REST Framework

### Database

* MySQL

---

## Project Structure

```
student_report/
│
├── students/
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
│
├── templates/
│   ├── index.html
│   ├── add_student.html
│
├── static/
│   ├── css/
│   ├── js/
│
├── manage.py
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/student-report.git
cd student-report
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Run the Server

```bash
python manage.py runserver
```

Open your browser and visit:

```
localserver
```

---

## API Endpoints

| Method | Endpoint        | Description            |
| ------ | --------------- | ---------------------- |
| GET    | /students/      | Retrieve all students  |
| POST   | /students/      | Add a new student      |
| GET    | /students/<id>/ | Retrieve a student     |
| PUT    | /students/<id>/ | Update student details |
| DELETE | /students/<id>/ | Delete a student       |

---

## Future Enhancements

* Student authentication
* Report card generation
* Attendance management
* Search and filtering
* PDF report export
* Email notifications

---

## Learning Outcomes

* Django Framework Development
* REST API Creation
* CRUD Operations
* Database Management
* Frontend-Backend Integration

---

## Author

**K. Koushal**
B.Tech Computer Science and Engineering

---

## License

This project is developed for educational and learning purposes.

