# Flask-Boilerplate-Managed-By-Techloset

Boilerplate for flask projects with best folder structure

# 1. Directory structure

Becaus Flask is a microframework it lets you decide on a lot of things. The structure of the Flask code is a personal view (or company view).

The directory structure that We recommend is:

<!-- ### A typical top-level directory layout -->

    ├── README.md
    ├── application
    │   ├── __init__.py
    │   ├── admin
    │   │   └── __init__.py
    │   ├── helpers
    │   │   └── __init__.py
    │   ├── utils
    │   │   └── __init__.py
    │   ├── webapp
    │   │   └── __init__.py
    │   └── wrappers
    │       └── __init__.py
    ├── config
    │   ├── __init__.py
    │   ├── default.py
    │   ├── development.py
    │   ├── production.py
    │   └── testing.py
    ├── deploy
    │   ├── flask_env.sh
    │   ├── gunicorn.conf
    │   ├── nginx.conf
    │   └── supervisor.conf
    ├── static
    │   └── __init__.py
    ├── templates
    │   └── __init__.py
    ├── tests
    │   └── __init__.py
    ├── manage.py
    └── requirements.txt

![Screenshot](structure.png)
