# contact management app

a full-stack web application for managing contacts built using react and flask.

---

## features

* create,read,update and delete contacts (crud)
* stores first name,last name and email
* rest api integration between frontend and backend

---

## tech stack

* react
* flask
* flask-cors
* flask-sqlalchemy
* python
* sqlite

---

## how to run locally

### 1. clone the repository

```bash
git clone https://github.com/your-username/contact-management-app.git
cd contact-management-app
```

---

### 2. backend setup (flask)

```bash
cd backend
python -m venv venv
venv\scripts\activate   # windows
# source venv/bin/activate  # mac/linux

pip install flask flask-sqlalchemy flask-cors
py main.py
```

backend runs on:

```text
http://localhost:5000
```

---

### 3. frontend setup (react)

```bash
cd frontend
npm install
npm run dev
```

frontend runs on:

```text
http://localhost:5173
```

---

## notes

* start backend first,then frontend
* make sure api urls match backend port

---

## learning outcomes

* building rest apis with flask
* integrating react frontend with flask backend
* implementing crud operations
* managing application state in react
* database integration using sqlalchemy and sqlite
* understanding full-stack web development fundamentals
