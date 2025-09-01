# 📝 ToDo List App with Django Admin

A simple ToDo list web application built with Django.  
This project uses the Django admin panel to manage tasks — including adding, editing, completing, and deleting tasks.

## 🔧 Features

- Add new tasks
- Edit existing tasks
- Mark tasks as completed
- Unmark tasks as not completed 
- Delete tasks

## 🚀 How to Run the Project Locally

1. Make sure you have Python 3.8+ installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/Afnan112/todo.git
   cd your-repo-name
   ```
3. Create virtual environment and install Django:
   ```bash
     pipenv shell
   ```
4. Activate the virtual environment:
   ```bash
     pipenv install django
   ```
5. Run migrations:
   ```bash
     python manage.py migrate
   ```
6. Create a superuser for accessing the admin panel:
   ```bash
     python manage.py createsuperuser
   ```
7. Run your Django Server:
   ```bash
     python manage.py runserver
   ```
8. Open the admin panel in your browser:
   ```bash
     http://127.0.0.1:8000/admin/
   ```

   
