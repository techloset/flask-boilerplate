# Flask-Boilerplate-Managed-By-Techloset

Boilerplate for flask projects with best folder structure

# 1. Directory structure

Because Flask is a microframework it lets you decide on a lot of things. The structure of the Flask code is a personal view (or company view).

The directory structure that We recommend is:

<!-- ### A typical top-level directory layout -->

    
    ├── application
    │   ├── admin
    │   │   ├── admin
    │   │   │    └── __init__.py
    │   │   ├── auth
    │   │   │    └── __init__.py
    │   │   ├── orders
    │   │   │    └── __init__.py
    │   │   ├── users
    │   │   │    └── __init__.py
    │   │   └── __init__.py
    │   ├── helpers
    │   │   └── __init__.py
    │   ├── utils
    │   │   └── __init__.py
    │   ├── webapp
    │   │   ├── auth
    │   │   │    └── __init__.py
    │   │   ├── orders
    │   │   │    └── __init__.py
    │   │   ├── products
    │   │   │    └── __init__.py
    │   │   ├── users
    │   │   │    └── __init__.py
    │   │   └── __init__.py
    │   │   
    │   ├── wrappers
    │   │   └── __init__.py
    │   └── __init__.py
    │
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
    ├── tests                                   # Test files (alternatively `spec` or `tests`)
    │   └── __init__.py
    ├── manage.py
    ├── README.md
    └── requirements.txt

![Screenshot](structure.png)
