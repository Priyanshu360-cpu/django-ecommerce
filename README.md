# Getting Started

Structure of a django project
```
TriArt3/
│
├── mac/
│   │
│   ├── migrations/
│   │   └── __init__.py
│   │
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── TriArt3/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── manage.py
```
Define a virtual env and activate it to start things of
```
 •$python3 -m venv env

 •$source env/bin/activate
```
Install django and it dependencies
```
 •(env) $ python -m pip install django
```
Setup your project to start things of
```
 •(env) $ django-admin startproject TechArt3
```
Start the app with the following command
```
 •(env) $ python manage.py startapp mac
```
💫 Start the project if you liked it :)
