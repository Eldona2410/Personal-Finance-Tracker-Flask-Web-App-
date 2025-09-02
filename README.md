# Personal-Finance-Tracker-Flask-Web-App-
A lightweight Flask web application to track income, expenses, and balance. It includes a backend powered by Flask + SQLite and a frontend built with HTML, CSS, and JavaScript.

A simple **Flask web app** to track income, expenses, and balance.  
It uses **Flask + SQLite** for the backend and a clean **HTML/JS frontend**.

---

## 🚀 Features
- Add income and expense transactions  
- View all past transactions  
- See income, expense, and balance summary  
- SQLite database with Flask SQLAlchemy  
- Lightweight and beginner-friendly project  

---

## 📂 Project Structure
finance-tracker/
│── server/ # Flask backend
│ ├── app.py
│ ├── requirements.txt
│
│── client/ # Frontend
│ └── index.html
│
│── README.md

yaml
Copy code

---

## 🛠️ Installation & Usage

### 1. Backend Setup (Flask)
```bash
cd server
pip install -r requirements.txt
python app.py
Runs the Flask API on http://127.0.0.1:5000.

2. Frontend Setup
Open client/index.html in your browser.
It will automatically connect to the Flask API.
