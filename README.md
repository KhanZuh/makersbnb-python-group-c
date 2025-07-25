
# 🏠 MakersBnB

A Python web application clone of Airbnb that allows users to list spaces and make bookings. 🌟

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Flask](https://img.shields.io/badge/flask-v3.0+-green.svg)
![PostgreSQL](https://img.shields.io/badge/postgresql-v12+-blue.svg)
![License](https://img.shields.io/badge/license-Educational-orange.svg)


## 🎯 Overview

MakersBnB is a full-stack web application built with Flask that mimics the core functionality of Airbnb. 
Users can register accounts, list spaces for rent, set availability windows, and make bookings. The application includes user authentication, form validation, and a PostgreSQL database with proper relational design.


## ✨ Features

- 🔐 **User Authentication**: Secure registration and login system with session management
- 🏡 **Space Management**: Users can list properties with descriptions, pricing, and photos
- 📅 **Availability System**: Hosts can define when their spaces are available for booking
- 🎫 **Booking System**: Guests can make reservations for available spaces
- 🛡️ **Form Validation**: Secure forms with CSRF protection using Flask-WTF
- 📱 **Responsive Design**: Clean HTML templates with navigation and user feedback

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| **Backend** | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) Python web framework |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) |
| **Forms** | Flask-WTF for secure form handling and validation |
| **Testing** | ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) with Playwright for end-to-end browser testing |
| **Frontend** | HTML templates with Jinja2 templating, CSS custom styling |
| **Environment** | Python virtual environment with pip |

## 🚀 Setup

### 📋 Prerequisites

- Python 3.8+ 🐍
- PostgreSQL 🐘
- pip (Python package manager) 📦

### ⚡ Installation


1. **📥 Clone the repository**
  ```bash
  git clone <repository-url>
  cd makersbnb-python
```

2. **🔧 Set up virtual environment**
 ```
 python -m venv makersbnb-venv
 source makersbnb-venv/bin/activate  # On Windows: makersbnb-venv\Scripts\activate
 ```
3. **📦 Install dependencies**
```
pip install -r requirements.txt

```

4. **🎭 Install Playwright for testing**
```
playwright install

```

5. **🗃️ Create databases**
```
createdb makers_bnb
createdb makers_bnb_test
```

6. **🔑 Set up environment variables: Create a .env file in the root directory:**
```
SECRET_KEY=your_secret_key_here
```

7. **🌱 Seed the database**
```
python seed_dev_database.py
```

8. **🎬 Run the application**
```
python app.py
```

9. **🌐 Visit the application**
Open your browser and go to `http://localhost:5001`






