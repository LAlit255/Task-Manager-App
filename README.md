# Task Manager Web App

A Task Manager web application built with Django, allowing users to register, log in, and manage their tasks. Users can create, edit, and delete tasks using a simple and intuitive interface.

## Features

- **User Authentication**: Registration and login functionality to manage personal tasks.
- **Task Management**: Create, view, edit, and delete tasks.
- **Django Forms and Models**: Built using Django's inbuilt forms and models to store task data in the database.



## Getting Started

### Prerequisites

- **Python** (3.6 or later)
- **Git**

### Quick Installation and Setup

Run the following commands in your terminal:

```bash
# Clone the repository, navigate into the directory, create a virtual environment, 
# activate it, install Django, apply migrations, create a superuser, and run the server
git clone https://github.com/your-username/task-manager.git && \
cd task-manager && \
python -m venv venv && \
source venv/bin/activate && \
pip install django && \
python manage.py migrate && \
python manage.py runserver
