# Django Todo App

This is a simple Todo application built with Django.

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- Mark tasks as completed

## Requirements

- Python 3.x
- Django 5.0.4
- asgiref 3.8.1
- sqlparse 0.5.0
- tzdata 2024.1

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/django-todo-app.git
   cd django-todo-app
   
2. Here's a basic `README.md` for your Django todo app:

```markdown
# Django Todo App

This is a simple Todo application built with Django.

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- Mark tasks as completed

## Requirements

- Python 3.x
- Django 5.0.4
- asgiref 3.8.1
- sqlparse 0.5.0
- tzdata 2024.1

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/django-todo-app.git
   cd django-todo-app
   ```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Apply the migrations:
   ```sh
   python manage.py migrate
   ```

5. Run the development server:
   ```sh
   python manage.py runserver
   ```

6. Open your web browser and navigate to `http://127.0.0.1:8000/` to see the application running.

## Usage

- To add a new task, fill in the form on the main page and click "Create Task".
- To update a task, click the "Update" link next to the task you want to update.
- To delete a task, click the "Delete" link next to the task you want to delete.
- To mark a task as completed, update the task and set the "completed" field to "Yes".
