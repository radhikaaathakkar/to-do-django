**To-Do App Backend**

This repository contains the backend implementation of a To-Do app built using Django. The app focuses on robust backend functionality, user authentication, and task management with CRUD operations.

**Features**

**User Authentication**
- Registration
- Login
- Logout

**Task Management**
- Create tasks
- View tasks specific to the logged-in user
- Update tasks
- Delete tasks

**Database**
- Uses SQLite for data storage
- Handles CRUD operations using Django ORM

**Project Structure**

**Setup Instructions**

**Prerequisites**
- Python 3.9+
- Django 4.2+

**Steps to Run**
1. Clone the repository:
    
    git clone <repository-url>
    cd todo_project
    

2. Create a virtual environment:
    
    python3 -m venv venv
    source venv/bin/activate
    

3. Install dependencies:
    
    pip install -r requirements.txt
  

4. Run migrations:
   
    python3 manage.py migrate
    

5. Create a superuser:
    
    python3 manage.py createsuperuser
    

6. Start the development server:
    
    python3 manage.py runserver
    

7. Access the app in your browser at:
   
    http://127.0.0.1:8000/
  
