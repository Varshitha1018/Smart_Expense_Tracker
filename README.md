# 💰 Smart Expense Tracker

A secure web-based personal finance management application built 
with Python and Flask.  
📌 MSc Computer Science Dissertation — **Distinction**

---

## 📋 About The Project

Smart Expense Tracker helps users manage personal finances with 
secure authentication, income and expense tracking, budget management, 
and a real-time dashboard for financial insights.

---

## ✨ Features

- 🔐 OTP-based email authentication with secure session management
- 👤 User registration, login, profile update and password reset
- 📊 Personal dashboard with income and expense overview
- 💾 CRUD modules for income, expenses, budgets and categories
- 📈 Reports and transaction history
- 🔔 Notifications system
- 🖼️ Profile image upload
- ✅ Form validation and error handling
- 🔗 RESTful architecture with Flask

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| Python | Backend language |
| Flask | Web framework |
| MySQL | Database |
| Flask-Bcrypt | Password hashing |
| Flask-Session | Session management |
| HTML5/CSS3 | Frontend templates |
| Jinja2 | Template engine |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- MySQL
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/Varshitha1018/Smart_Expense_Tracker.git

cd Smart_Expense_Tracker

# Install dependencies
pip install flask flask-session flask-bcrypt mysql-connector-python itsdangerous werkzeug

# Set up the database
# Import exp_tacker_dump.sql into your MySQL

# Update database credentials in app.py
host='localhost'
user='root'
password='your_db_password'
database='exp_tracker'

# Run the application
python app.py
```

---

## 📁 Project Structure

Smart Expense Tracker
├── app.py              # Main application file
├── otp.py              # OTP generation
├── cmail.py            # Email sending
├── exp_tacker_dump.sql # Database schema
├── static/             # Images and uploads
└── templates/          # HTML templates


---

## 👩‍💻 Author

**Varshitha Edula**  
🔗 [LinkedIn](https://www.linkedin.com/in/varshitha-edula)  
📧 varshithareddyedula@gmail.com
