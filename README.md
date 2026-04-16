# 🔐 Password Strength Checker

A simple Python program that evaluates password strength using length and pattern matching with regular expressions.

## 📌 Overview
This project checks a user-provided password and classifies it into three levels:
- **Not Safe** – fewer than 8 characters  
- **Medium** – meets length requirement but lacks stronger security patterns  
- **Safe** – includes at least one uppercase letter and one special character  

It’s designed as a beginner-friendly example of input validation and basic security practices in Python.

## 🚀 Features
- Validates minimum password length  
- Detects uppercase letters (`A–Z`)  
- Detects special characters (`@$*#~?!&`)  
- Clean and easy-to-understand logic  

## 🧠 How It Works
The program:
1. Prompts the user to enter a password  
2. Checks its length  
3. Uses the `re` module to search for required patterns  
4. Outputs the password strength classification  

## 🛠️ Requirements
- Python 3.x

## ▶️ Usage
Run the script:

```bash
python password_checker.py
