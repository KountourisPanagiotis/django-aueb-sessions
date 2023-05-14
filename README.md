# django-aueb-sessions

## Athens University of Economics and Business ([AUEB](https://aueb.gr/))
Several [Coding Factory](https://codingfactory.aueb.gr/) @ [AUEB](https://aueb.gr/) Python Projects. 🐍
Django backend projects.

## Projects info and usage
1. ## *Introduction to Django*
    - Django REST API (DRF) - JSON - ENDPOINTS
    - Connection with SPA(Single Page Application)
2. ## *Introduction to Django Rest Framework (DRF)*
    - DRF - REST API
    - Serialization - Deserialization - Serializer - ModelSerializer
    - Function/Class Bases API Views
    - Browsable API
    - Validation Criteria for input
3. ## *DRF advanced*
    - GenericAPIView and Mixins
    - Generic Classs Based Views
    - REST API for website that provides ebooks 📚
    - Permissions system only for users with account
    - Users can see a list of available ebooks and add new ebooks 📘
    - Users can make a review for a ebook ✍️
4. ## *DRF Final*
    - Authentication
    - REST registration and Authentication (Django-REST-Auth)
    - Viewset and Router classes
    - DRF filters
    - Automated tests with Django and DRF

## Installation
To install and run a project, follow these steps:
1. Clone the repository to your local machine
2. `cd` from the terminal to the project you want to run
3. `python -m venv venv` create python Virtual Environment
4. `source\Scripts\activate` activate the virtual environment
5. `pip install -r requirements.txt` install dependencies from requirements.txt
6. `cd` to the project folder e.g. newsapi
7. `python manage.py makemigrations` prepare database for any migration changes
8. `python manage.py migrate` to migrate
9. `python manage.py createsuperuser` to create a superuser admin
10. `python manage.py runserver` to run the server
11. `http://127.0.0.1:8000/` Check the development server at the browser 💻
