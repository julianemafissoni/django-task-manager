# Task Manager API

A REST API for managing personal tasks built with Django and Django REST Framework.

## Features

* User authentication
* Create, update, delete and list tasks
* Filter tasks by status
* Search tasks by title or description
* Ordering results
* Pagination
* Interactive API documentation

## Technologies

* Python
* Django
* Django REST Framework
* Django Filter
* drf-spectacular (OpenAPI / Swagger)

## Installation

Clone the repository:

git clone https://github.com/julianemafissoni/django-task-manager.git

Enter the project folder:

cd django-task-manager

Create virtual environment:

python -m venv .venv

Activate it:

Windows:
.venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py migrate

Start the server:

python manage.py runserver

The API will be available at:

http://127.0.0.1:8000/

## API Endpoints

### List Tasks

GET

/api/tasks/

### Create Task

POST

/api/tasks/

### Filter Tasks by Status

/api/tasks/?status=pending

### Search Tasks

/api/tasks/?search=python

### Ordering Tasks

/api/tasks/?ordering=-created_at

### Pagination

/api/tasks/?page=2

## API Documentation

Interactive documentation is available at:

/api/docs/

## Author

Juliane Mafissoni
