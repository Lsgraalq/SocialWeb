# SocialWeb

> **Created: January 2024** — learning project (Django authentication).

A **Django** project focused on learning **user authentication** — the starting point of a social web app. It implements a custom login flow using Django's auth system.

## What it does

- An `account` app with a **login form** (`LoginForm`) and a `user_login` view that:
  - authenticates the user with `authenticate()`
  - logs them in with `login()`
  - handles invalid credentials and disabled accounts.
- Login template extending a shared `base.html`.

> This is an early stage of the project — the authentication foundation. Models and further social features were still to come.

## Running

```bash
pip install django
python manage.py migrate
python manage.py runserver
```

Then open `/account/login/`.

## Stack

- Python 3
- Django
- SQLite
