# [Job Board App Using Django](https://job-board-app-using-django.onrender.com/)

A practice project to develop a job board web application using Django and HTML.

## Features

- User authentication (Sign up, Login, Logout)
- Create, read, update, and delete (CRUD) job postings
- Responsive design for better user experience
- Search functionality for job listings
- Admin panel to manage jobs and users

## Installation

Follow these steps to set up the project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/vdanepalli/job_board_app_using_django.git
   cd job_board_app_using_django
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```
6. Open your browser and navigate to:
   ```code
   http://127.0.0.1:8000/
   ```
