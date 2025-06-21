# 📝 BLOG — Personal Blog Website

A clean and simple blog web application built using **Python** and **Django**.  
Users can register, log in, create, edit, and delete blog posts. Designed for personal learning and showcasing Django fundamentals.

## 🚀 Features

- User authentication (Sign Up, Login, Logout)
- Create, edit, delete posts
- Browse and read articles
- Clean, responsive UI with Bootstrap

## 🛠️ Tech Stack

- Python 3.11+
- Django 4.x
- SQLite
- HTML, CSS, Bootstrap 5

## 📦 Setup

```bash
git clone https://github.com/Shivanikinagi/BLOG.git
cd BLOG
python -m venv venv
venv\Scripts\activate  # or source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
