# 🏦 Bank Management System (FastAPI)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-00a393.svg)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57.svg)
![Jinja2](https://img.shields.io/badge/Jinja2-Templates-red.svg)
![Status](https://img.shields.io/badge/Status-Live-success.svg)

A lightweight, fast, and secure web-based Bank Management System built using **FastAPI**, **SQLite**, and **Jinja2 Templates**. This application allows users to create accounts, securely log in, and perform basic banking operations like deposits, withdrawals, and balance inquiries in real-time.

---

## 🚀 Live Demo
**Test the application live here:** [Bank Management System - Live Portal](https://bank-system-using-fastapi-project.onrender.com/login)

---

## ✨ Key Features
* **User Authentication:** Secure Sign-Up and Login functionality.
* **Data Validation:** Strict input validation for passwords and emails using `Pydantic` and `EmailStr`.
* **Deposit Funds:** Add money to the account seamlessly.
* **Withdraw Funds:** Secure withdrawals with built-in "Insufficient Balance" handling.
* **Real-time Balance:** Instant calculation and reflection of the current account balance.
* **Responsive UI:** Clean and interactive user interface built with HTML/CSS and Jinja2.

---

## 🛠️ Tech Stack
* **Backend:** Python, FastAPI
* **Database:** SQLite3 (Relational Database)
* **Frontend:** HTML5, CSS3, Jinja2 Templates
* **Validation:** Pydantic

---

## 📂 Project Structure
```text
├── Projects/
│   └── BankSystem/
│       ├── main.py                 # FastAPI application instance & DB setup
│       ├── logic.py                # Core business logic, routing, and Pydantic models
│       ├── login.html              # UI for User Login
│       ├── signup.html             # UI for Account Registration
│       ├── services.html           # Main dashboard UI (Deposit, Withdraw, Balance)
│       └── BankMangementSystem.db  # SQLite Database
├── requirements.txt                # Project dependencies
└── README.md                       # Project documentation
