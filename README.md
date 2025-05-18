# ALX Travel App

A Django-based travel listing platform with REST API support and Swagger documentation.

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Unix/macOS
# or
.\venv\Scripts\activate  # On Windows
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a .env file:
```bash
cp .env.example .env
```
Then edit the .env file with your database credentials and other settings.

4. Set up the database:
```bash
python manage.py migrate
```

5. Run the development server:
```bash
python manage.py runserver
```

## Features

- Django REST Framework for API development
- Swagger documentation at /swagger/
- MySQL database integration
- CORS support
- Celery for background tasks
- Environment variable management

## API Documentation

Access the Swagger documentation at `/swagger/` when the server is running. 