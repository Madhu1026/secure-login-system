# Secure Login System

A Python Flask secure login web application with:

- User registration
- bcrypt password hashing
- SQLite database
- Input validation
- Parameterized SQL queries
- Session-based authentication
- Protected dashboard
- Logout

## Requirements

Python 3.9+ recommended.

## Installation

Open a terminal in this project folder:

```bash
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

Open:

http://127.0.0.1:5000

## Test

1. Open Create Account.
2. Register with a strong password.
3. Login.
4. Open the dashboard.
5. Logout.
6. Try opening /dashboard after logout.

## Security notes

For production, set a strong random SECRET_KEY as an environment variable, use HTTPS, disable debug mode, use secure cookies, add CSRF protection and rate limiting, and use a production-ready database/session store.
