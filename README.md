# Django User Authentication App

> Python Django app for user registration and login

## Quick Start

```bash
# Install dependencies
pipenv install

# Serve on localhost:8000
python manage.py runserver
```

## Routes

The application provides the following routes:

| Route               | Method    | Description                        |
| ------------------- | --------- | ---------------------------------- |
| `/accounts/login/`  | GET, POST | User login form and authentication |
| `/accounts/logout/` | GET       | Log out current user               |
| `/accounts/signup/` | GET, POST | Create a new user account          |
| `/`                 | GET       | Landing page                       |
| `/admin/`           | GET       | Django admin panel                 |

## References

Acknowledgement: This repo was created following the tutorial by Net Ninja
: "Django Tutorial #19 - User Creation Form" https://www.youtube.com/watch?v=baKm-YB_Ibc&list=PL4cUxeGkcC9ib4HsrXEYpQnTOTZE1x0uc&index=19
