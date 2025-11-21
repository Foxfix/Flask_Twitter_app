# Flask Twitter App 🐦

[![Python](https://img.shields.io/badge/python-3.10-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.x-orange)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A simple Flask application that integrates with the Twitter API, retrieves tweets, performs sentiment analysis, and visualizes them.

---

## Features ✨

- Log in with Twitter using OAuth
- Retrieve latest tweets based on search queries
- Perform sentiment analysis on tweets
- Color-coded tweets by sentiment
- PostgreSQL database for user and tweet management
- Simple web interface using Flask

---

## Installation ⚡

Clone the repository:

```bash
git clone https://github.com/Foxfix/Flask_Twitter_app.git
cd Flask_Twitter_app
```

Create and activate a virtual environment:

```
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

Install dependencies:
```pip install -r requirements.txt```

## Configuration 🛠️

1. Создай Twitter developer account и получи **consumer keys**.
2. Создай PostgreSQL базу и таблицу:


```sql
CREATE TABLE users(
    id SERIAL PRIMARY KEY,
    screen_name text,
    oauth_token text,
    oauth_token_secret text
);
```
Update your app.py with database credentials:

```
Database.initialise(database='your_db', host='localhost', user='your_user', password='your_password')
```

Usage 🚀

Run the Flask app:
```python app.py```

Open your browser at http://127.0.0.1:4995

Technologies 🛠️

Python 3.10+
Flask
PostgreSQL
Twitter API
Sentiment Analysis API

License 📄

This project is licensed under the MIT License.





