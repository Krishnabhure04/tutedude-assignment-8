# Django User Registration & Login Project

## 📚 Module 14 Assignment

This Django project integrates both **User Registration** and **Login/Logout** functionalities into a single web application.

---

## 🚀 Features

- User **Registration** with form validation
- User **Login** & **Logout**
- Simple **dashboard/homepage** after login
- Django's built-in **User** model and authentication system
- Modular structure with reusable templates

---

## 🛠️ Technologies Used

- Python 3.x
- Django (≥3.0)

---

## 📂 Project Structure
user_auth_project/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md
│
├── user_auth_project/
│ ├── settings.py, urls.py, ...
│
└── accounts/
├── views.py, models.py, forms.py, ...
├── templates/accounts/
├── login.html
├── register.html
└── dashboard.html

---

## 🧪 How to Run the Project

1. **Install dependencies:**
---
bash
pip install -r requirements.txt


2. **Run migrations:**
python manage.py makemigrations
python manage.py migrate

3. **Start the server:**
python manage.py runserver

4. **Open in browser:**

Visit http://127.0.0.1:8000/register/ to create a new user

Visit http://127.0.0.1:8000/login/ to log in

Visit http://127.0.0.1:8000/logout/ to log out

---
