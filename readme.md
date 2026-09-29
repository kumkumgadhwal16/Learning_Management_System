# Learning Management System (LMS)

A **Learning Management System (LMS)** is a web-based application designed to manage online learning activities. It allows students to access courses and learning materials, while administrators/instructors can manage courses, students, and educational content.

## 🚀 Features

* User Registration and Login
* Student Dashboard
* Admin/Instructor Dashboard
* Course Management
* Add, Update and Delete Courses
* View Course Details
* Learning Materials
* Student Enrollment
* Track Student Progress
* Search Courses
* User Profile Management
* Responsive User Interface

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, Bootstrap
* **Backend:** Python, Django
* **Database:** postgres
* **Programming Language:** Python
* **Tools:** VS Code, Git, GitHub,docker

## 📂 Project Structure

```text
Learning_Management_System/
│
├── manage.py
├── db.sqlite3
│
├── lms/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── courses/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── templates/
│
├── users/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── templates/
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/learning-management-system.git
```

### 2. Open the Project

```bash
cd learning-management-system
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Create Admin Account

```bash
python manage.py createsuperuser
```

Enter your username, email and password when prompted.

### 8. Run the Server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## 👥 User Roles

### Student

Students can:

* Register and login
* Browse available courses
* Enroll in courses
* View course content
* Access learning materials
* Track their learning progress

### Admin / Instructor

Admin or instructors can:

* Manage students
* Create courses
* Update courses
* Delete courses
* Add learning materials
* Manage enrollments
* Monitor student progress

## 🗄️ Main Database Models

The project can contain the following models:

* **User** – Stores user information
* **Course** – Stores course details
* **Enrollment** – Stores student course enrollments
* **Lesson** – Stores individual lessons
* **Progress** – Tracks student learning progress

## 🔄 Application Workflow

```text
User Registration
       ↓
     Login
       ↓
 Student Dashboard
       ↓
 Browse Courses
       ↓
 Select Course
       ↓
    Enroll
       ↓
 Access Lessons
       ↓
 Complete Lessons
       ↓
 Track Progress
```

## 🎯 Project Objective

The main objective of this project is to provide a simple and efficient platform for managing online education. The system helps students access learning resources and allows administrators/instructors to manage courses and student activities from a centralized platform.

## 🔮 Future Enhancements

* Online quizzes and exams
* Assignment submission
* Course certificates
* Video lectures
* Student notifications
* Online payment integration
* Course ratings and reviews
* Advanced progress analytics
* REST API integration
* Deployment on cloud platforms

## 📸 Screenshots

Add screenshots of your project here.

Example:

```text
Home Page
Login Page
Student Dashboard
Course Page
Admin Dashboard
```

## 🤝 Contribution

Contributions are welcome. If you want to improve this project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Create a Pull Request

## 📄 License

This project is created for educational and learning purposes.

---

### 👩‍💻 Author

**Kumkum Gadhwal**

Learning and building projects with **Python and Django**.
