# Contact Management App

A full-stack web application for managing contacts built using React and Flask.

---

## 🚀 Features

* Create,read,update,delete contacts (CRUD)
* Stores first name,last name and email
* REST API integration between frontend and backend

---

## 🛠️ Tech Stack

* React
* Flask
* Flask-CORS
* Flask-SQLAlchemy
* Python
* SQLite

---

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/contact-management-app.git
cd contact-management-app
```

---

### 2. Backend Setup (Flask)

```bash
cd backend   # if backend folder exists
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux

pip install flask flask-sqlalchemy flask-cors
py main.py
```

Backend runs on:

```
http://localhost:5000
```

---

### 3. Frontend Setup (React)

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173   # (Vite default)
```

---

## 📌 Notes

* Start backend first,then frontend
* Make sure API URLs match backend port
