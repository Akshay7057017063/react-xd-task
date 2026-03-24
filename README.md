# PopX React Challenge – Login Credentials

## 📌 Overview

This project includes a simple login system with frontend validation. The credentials are currently hardcoded for testing purposes.

---

## 🔐 Demo Login Credentials

Use the following credentials to log in:

* **Email:** [test@popx.com](mailto:test@popx.com)
* **Password:** 123456

---

## ⚙️ Validation Rules

The login form includes the following validations:

* Email is required
* Password is required
* Email must be in a valid format
* Invalid credentials will show an alert message

---

## 🚀 Behavior

* If fields are empty → shows alert:
  `Please enter Email and Password`

* If email is invalid → shows alert:
  `Please enter a valid email address`

* If credentials are incorrect → shows alert:
  `Invalid credentials`

* If credentials are correct → redirects to `/account`

---

## 🛠 Tech Stack

* React.js
* React Router DOM
* Tailwind CSS

---

## 📎 Notes

This is a frontend-only implementation. In a real-world application:

* Credentials should be verified via backend API
* Passwords must be securely hashed
* Authentication should use JWT or session-based auth

---

## 👨‍💻 Aut
