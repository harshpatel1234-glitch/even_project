# 🚀 Django ORM - Even ID Validation & Edit Control

This project is developed as part of my **Internship Task at BrainyBeam**.  
It demonstrates how to use **Django ORM** to enforce **business rules** where:

- ✅ Only records with **EVEN IDs** can be edited  
- ❌ Records with **ODD IDs** are blocked and show an error  

---

## 🎯 Task Requirement

> **Use ORM query which will get the objects of even number ID, also can edit the form of only even ID else should show error.**

This requirement is implemented **strictly at backend level** using Django ORM and view-level validation.

---

## 🧠 Core Concept Used

- Django ORM filtering (`id__mod`)
- Backend validation (`id % 2`)
- Secure form editing
- Error handling for invalid access

---

## 🛠️ Tech Stack

- 🐍 Python 3.13  
- 🌐 Django 4.2  
- 🗄️ SQLite3  
- 🎨 HTML (Django Templates)

---

## 📁 Project Structure

