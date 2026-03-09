# Django Task Manager

A simple task management API built with Python and Django.

## Tech Stack

* Python
* Django
* Django REST Framework
* SQLite

## Features

* Create tasks
* List tasks
* Update tasks
* Delete tasks

## Setup

Clone the repository:

git clone https://github.com/YOUR-USERNAME/django-task-manager.git

Go to the project folder:

cd django-task-manager

Create a virtual environment:

python -m venv .venv

Activate the environment:

.venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py migrate

Start the server:

python manage.py runserver

## API Endpoints

GET /api/tasks/
POST /api/tasks/
PUT /api/tasks/{id}/
DELETE /api/tasks/{id}/
