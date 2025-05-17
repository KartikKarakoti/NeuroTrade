# NeuroTrade
#### Video Demo:  <https://youtu.be/MCJp6WTDjXo?feature=shared>
#### Description: An AI-powered stock trading simulation platform built as part of the CS50x: Introduction to Computer Science course. NeuroTrade mimics a real-time trading experience with features like stock quoting, portfolio tracking, and transaction history.

---

## 🚀 Features

- 🔐 User authentication (register/login/logout)
- 📈 Real-time stock lookup using IEX API
- 🛒 Buy & sell shares with live pricing
- 💼 View portfolio with current holdings and available cash
- 🕒 View transaction history
- ⚙️ Built with Python, Flask, SQLite, and Jinja2 templates

---

## 💻 Tech Stack

- **Frontend**: HTML, CSS, Jinja2 (Flask templates)
- **Backend**: Python, Flask
- **Database**: SQLite
- **APIs**: [IEX Cloud](https://iexcloud.io) for real-time stock prices

---

## 🏗️ Project Structure

NeuroTrade/
│
├── app.py # Flask app and routing
├── helpers.py # Custom helper functions (e.g., API lookups)
├── finance.db # SQLite database
├── templates/ # HTML templates
│ ├── layout.html
│ ├── login.html
│ ├── register.html
│ ├── quote.html
│ ├── buy.html
│ ├── sell.html
│ └── index.html
├── static/ # Optional CSS or image files
└── README.md


---

## 🔐 Authentication & Sessions

- Uses Flask-Session to manage user sessions
- Passwords hashed securely with Werkzeug

---

## 📚 What I Learned

- How to build full-stack web apps with Flask and SQLite
- API integration (stock data from IEX)
- Session management and security in web apps
- Dynamic rendering using Jinja2 and Bootstrap

---

## 📦 Installation (Optional)

To run this locally:
```bash
git clone https://github.com/yourusername/NeuroTrade.git
cd NeuroTrade
pip install -r requirements.txt
flask run
