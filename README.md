# Django reCAPTCHA Integration

## 📌 Overview
This project demonstrates how to integrate **Google reCAPTCHA** into a Django form to protect against automated submissions (bots).  
It uses the `django-recaptcha` library and Google’s reCAPTCHA v2 checkbox.

---

## 🚀 Features
- Django form with reCAPTCHA field
- Validation against Google’s reCAPTCHA API
- Secure storage of keys using `.env`
- Example contact form with name, email, and message
---
## Setup Instruction
```bash
pip install django-recaptcha
```
Add keys to `.env` file
```bash
RECAPTCHA_PUBLIC_KEY=your_site_key
RECAPTCHA_PRIVATE_KEY=your_secret_key
```
