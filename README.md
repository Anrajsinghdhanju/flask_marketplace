## Flask Marketplace App

This is a beginner-friendly full-stack web application built using **Flask** and **SQLAlchemy**. Users can:

- Register and log in securely
- View a list of items
- Purchase items if they have enough virtual budget
- Track ownership of purchased items

### Tech Stack

- Python (Flask, SQLAlchemy, Flask-Login, Flask-WTF)
- SQLite (local development database)
- Bootstrap (for UI styling)

### Getting Started

1. Clone the repo
2. Set up a virtual environment
3. Install dependencies with `pip install -r requirements.txt`
4. Create the database:
```python
from market import app, db
with app.app_context():
    db.create_all()
