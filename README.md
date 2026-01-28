# REST API – User Authentication

A simple and secure RESTful API built with **Python (Flask)** that provides user registration and login functionality using **JWT authentication**.

---

## ✨ Features

* User Registration
* User Login
* JWT-based Authentication
* Protected Routes
* Secure Password Handling
* RESTful Architecture

---

## 🛠 Tech Stack

* Python
* Flask
* Flask-RESTful
* Flask-JWT-Extended
* Flask-SQLAlchemy
* SQLite / MySQL

---

## 📌 API Endpoints

| Method | Endpoint   | Description         |
| -----: | ---------- | ------------------- |
|   POST | /register  | Register new user   |
|   POST | /login     | User login          |
|    GET | /protected | Protected API (JWT) |

---

## 🔐 Authentication Flow

1. User registers using the **Register API**
2. User logs in using valid credentials
3. Server returns a **JWT token**
4. Token is sent in headers to access protected APIs

---

## 🚀 How to Run the Project

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

---

## 📂 Project Use Case

This API can be used as a backend for:

* Web Applications
* Mobile Applications
* Any system requiring secure user authentication

---

## 👨‍💻 Author

Developed by **Hiten**

---

## 📜 License

This project is open-source and free to use for learning purposes.
