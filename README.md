# 💰 Personal Finance Manager — Full Stack Web App

A full-stack Personal Finance Manager web application built using Flask and SQLAlchemy that allows users to securely track, manage, analyze, and export their expenses through an interactive dashboard.

This project demonstrates backend development, authentication, database design, analytics visualization, and structured web app architecture.

---

## 🚀 Features

### 👤 User Authentication
- User registration and login
- Session management
- User-specific expense data isolation

### 💸 Expense Management
- Add expenses with title, amount, category, and date
- Delete expenses
- Category tagging
- Date tracking

### 📊 Analytics Dashboard
- Total spending summary
- Category-wise expense breakdown
- Pie chart visualization using Chart.js

### 🔎 Filters
- Filter expenses by category
- View focused spending segments

### 📁 Data Export
- Export all expenses to CSV file

---

## 🧱 Tech Stack

Backend:
- Python
- Flask
- Flask-SQLAlchemy
- Flask-Login

Frontend:
- HTML
- CSS
- Jinja2 Templates
- Chart.js

Database:
- SQLite

---

## 📂 Project Structure

finance-manager/
│
├── app.py
├── models.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── add_expense.html
│
└── static/
    ├── css/style.css
    └── js/dashboard.js

---

## ⚙️ Installation & Run

### 1️⃣ Clone repo

git clone <YOUR_REPO_URL>
cd finance-manager

### 2️⃣ Install dependencies

pip install -r requirements.txt

### 3️⃣ Run app

python app.py

### 4️⃣ Open browser

http://127.0.0.1:5000/login

---

## 🧪 Usage Flow

1. Register new user  
2. Login  
3. Add expenses  
4. View dashboard analytics  
5. Filter by category  
6. Export CSV report  

---

## 📊 Example Use Cases

- Personal expense tracking
- Monthly budget monitoring
- Category-based spending analysis
- Student finance management
- Prototype for SaaS finance apps

---

## 🔐 Note

Passwords are stored as plain text in this demo version.  
For production use, password hashing should be added.

---

## 🎓 Project Type

Academic / Portfolio Major Project  
Suitable for B.Tech / Final Year / Full-Stack Portfolio

---

## 🔮 Future Enhancements

- Password hashing
- Monthly reports
- Budget alerts
- Recurring expenses
- Multi-user roles
- Cloud database support
- Deployment on cloud platform

---

## 👩‍💻 Author

Your Name  
Full Stack + AI Developer
