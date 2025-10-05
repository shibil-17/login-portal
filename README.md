# Login & Registration Portal

## Project Description
This is a secure login and registration portal built with **Flask** and **SQLite**.  
It allows users to register, log in, log out, and access a personal dashboard.  
Admins can view the details of all registered users.

---

## Features

- **User Registration:** Create accounts with unique username and email.  
- **Password Security:** Passwords hashed using `Werkzeug` for safe storage.  
- **User Login:** Authenticated users can log in and see their dashboard.  
- **Admin Access:** Only admins can view all registered users.  
- **Rate Limiting:** Prevents brute-force attacks using `Flask-Limiter`.  
- **Flash Messages:** Display success/error notifications for actions.  

---

## Screenshots

### Registration Page
<img width="1919" height="995" alt="Login Screenshot" src="https://github.com/user-attachments/assets/56a93297-9c5f-4e28-b332-c7c9aa6f8b2c" />

### Login Page
<img width="1918" height="999" alt="Registration Screenshot" src="https://github.com/user-attachments/assets/165246a4-5db8-4bca-9863-011e6d73985d" />

### Dashboard Page
<img width="1919" height="993" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/ab274c99-2634-4636-a672-7a41663c73b4" />

---

## Security Measures

- **Password Hashing:** Stored hashed passwords using `Werkzeug`.  
- **SQL Injection Prevention:** Using SQLAlchemy ORM instead of raw SQL queries.  
- **Rate Limiting:** Limits login and registration attempts to prevent attacks.  
- **Secret Key Security:** `app.secret_key` stored as environment variable.  
- **Optional Password Validation:** Can enforce minimum 8 characters, symbols, numbers, uppercase letters using regex.  

---

## 🛠️ Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/shibil-17/my-portfolio.git
```
2.Open the project in VS Code
```bash
cd my-portfolio
code .
```
3.Run the Flask app
```bash
python app.py
```
