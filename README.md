# Django Task Manager

A simple Task Manager web application built with **Django**, **Bootstrap**, and **SQLite**.

This project allows users to register, log in, and manage their personal tasks with full CRUD functionality.

## Live Demo

🔗 **Live Website:** [https://task-manager-dck2.onrender.com/](https://task-manager-dck2.onrender.com/)

---

## Features

- User signup
- User login/logout
- User dashboard
- Create tasks
- View personal task list
- Edit tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Admin panel for managing users and tasks

---

## Tech Stack

- **Backend:** Django
- **Frontend:** HTML, Bootstrap
- **Database:** SQLite
- **Authentication:** Django built-in auth system

---

## Project Structure

```bash
taskmanager/
│
├── manage.py
├── requirements.txt
├── build.sh
├── Procfile
├── runtime.txt
│
├── taskmanager/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── tasks/
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── urls.py
    ├── views.py
    ├── migrations/
    └── templates/
        └── tasks/
            ├── base.html
            ├── dashboard.html
            ├── task_list.html
            ├── task_form.html
            ├── task_confirm_delete.html
            ├── signup.html
            └── login.html