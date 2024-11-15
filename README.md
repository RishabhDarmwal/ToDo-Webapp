# ToDo-Webapp

![image](https://github.com/user-attachments/assets/87dfb99a-64df-4f40-822d-7bb67da9a58c)

A web-based task management application built with Django, designed to help users organize and manage their to-do lists efficiently.

## Features
- Add, update, and delete tasks.
- Simple, user-friendly interface.
- Task management on the go.
## Usage
- Home Page: On the home page, you can view, add, update, and delete tasks.
- Add Task: Enter your task and click "Add" to add it to the list.
- Delete Task: Click the "Delete" button next to any task to remove it.


## Prerequisites
- Python 3.6+ (recommended)
- Django 3.0+
- A browser to access the web app

## Installation

## 1. Clone the Repository

 First, clone this repository to your local machine either using GitHub Desktop or the following command in GitBash:
 
 git clone https://github.com/<your-github-username>/ToDo-Webapp.git


## 2. Set Up a Virtual Environment (optional but recommended)
 Create a virtual environment to manage dependencies:

  # Windows
  python -m venv env
  
  # macOS/Linux
  python3 -m venv env

 Activate the virtual environment:

  # Windows
  env\Scripts\activate
  
  # macOS/Linux
  source env/bin/activate

## 3. Install Dependencies
 Install the required dependencies from requirements.txt:

  pip install -r requirements.txt

## 4. Run Migrations
 To set up the database, run the following Django commands:
  python manage.py migrate
## 5. Run the Development Server
 Start the server to access the app locally:
  python manage.py runserver

## The app will be accessible at http://127.0.0.1:8000/ in your web browser.

