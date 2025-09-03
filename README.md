# 🔑 Flask Login System

A simple **Flask-based user authentication system** with registration, login, and session management.  
It uses **SQLite** for storing user details and **SQLAlchemy ORM** for database interactions. 
[Live Demo](https://login-register-web-application-1.onrender.com)


---

## 🚀 Features
- User Registration (Name, Email, Password, Phone, Address)
- Secure Password Hashing (using `werkzeug.security`)
- User Login & Logout
- Session Management
- SQLite Database (`app.db`)
- Flask + SQLAlchemy + Jinja2 templates

---

## 🛠 Tech Stack
- [Python 3.x](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Werkzeug](https://werkzeug.palletsprojects.com/)
- [SQLite](https://www.sqlite.org/)

---

## 📂 Project Structure
python-app/
│── app.py # Main Flask application
│── requirements.txt # Dependencies
│── instance/ # Holds SQLite database
│ └── app.db
│── templates/ # HTML Templates (login.html, register.html, home.html)
│── static/ # CSS, JS, Images
│── venv/ # Virtual Environment (ignored in git)
└── README.md # Project Documentation


---

## ⚡ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/flask-login-app.git
cd flask-login-app
2️⃣ Create Virtual Environment & Activate
python -m venv venv
venv\Scripts\activate      # On Windows
source venv/bin/activate   # On Linux/Mac

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Initialize Database
python
>>> from app import db
>>> db.create_all()
>>> exit()

5️⃣ Run the Flask App
python app.py


App will run on:
👉 http://127.0.0.1:5000/

SCREENSHOTS
REGISTER=>
<img width="1920" height="1080" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/e31c20c1-6f37-4fd7-8529-02c06927ae56" />

LOGIN=>
<img width="1920" height="1080" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/04e463f6-acf1-4175-a8ec-784ebf09468b" />
DESHBORD=>
<img width="1920" height="1080" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/dd31a7d5-91cd-46ee-a39f-3b014a63fea0" />


📝 License

This project is licensed under the MIT License – feel free to use and modify it.
