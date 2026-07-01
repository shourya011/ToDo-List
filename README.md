#  Django Todo List

A simple Todo List web application built with Django that allows users to create, update, complete, and delete tasks.

##  Features

- Add new tasks
- Mark tasks as completed
- Edit existing tasks
- Delete tasks
- View all tasks in one place
- Clean and responsive user interface

##  Tech Stack

- Python
- Django
- HTML
- CSS
- SQLite (Default Django Database)

##  Project Structure

```
todo_project/
│
├── todo_app/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── todo_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
└── db.sqlite3
```

##  Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd todo_project
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install django
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

##  Screenshots

Add screenshots of your application here.

##  Future Improvements

- User Authentication
- Task Categories
- Due Dates
- Search and Filter Tasks
- Dark Mode
- REST API Integration

##  Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

##  License

This project is open-source and available under the MIT License.

Learning GitHub badges
