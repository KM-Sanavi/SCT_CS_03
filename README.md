# 🔐 Password Strength Checker Tool

A simple program that assesses the **strength of a password** based on multiple security criteria such as length, presence of uppercase and lowercase letters, numbers, and special characters.

---

## 📌 Project Overview

This project evaluates how strong a user's password is by checking whether it meets essential security requirements.  
It helps users create more secure passwords and understand what makes a password strong or weak.

---

## 🧠 Password Strength Criteria

The password will be evaluated based on:

- ✔️ Minimum length requirement (e.g., 8 characters)
- ✔️ Contains **uppercase letters**  
- ✔️ Contains **lowercase letters**  
- ✔️ Contains **numbers (0-9)**  
- ✔️ Contains **special characters** (! @ # $ % etc.)

Based on the combination of criteria met, the tool will classify the password as:

- **Weak**
- **Medium**
- **Strong**
- **Very Strong**

---

## 🧩 Features

- Real-time classification of password strength  
- Easy to modify or expand criteria  
- Clear feedback on what is missing  
- Supports all types of characters  

---

## 🛠️ Technologies Used

- Python (or your chosen language)
- Regular expressions (optional but recommended)
- Basic string analysis  

---

## 👨‍💻 Sample Code (Python)

```python
import re

def check_password_strength(password):
    strength_score = 0

    # Criteria
    if len(pa
