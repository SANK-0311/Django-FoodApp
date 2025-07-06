````markdown
# 🍴 Django FoodApp

A simple and elegant Django web application that allows users to **register, login, and manage food items** with full CRUD functionality. Built using Django and Bootstrap 5 for a modern and responsive UI.

---

## 🌟 Features

- ✅ User registration and login system
- ✅ Add, view, and delete food items
- ✅ Clean and responsive UI with Bootstrap 5
- ✅ User-specific item posting
- ✅ Custom user profile model with image and location
- ✅ Flash messages for login/logout/signup events
- ✅ Full authentication (login required for protected pages)

---

## 📷 Screenshots

![HomePage](Screenshots/HomePage.png)

---

## 🛠️ Tech Stack

- **Backend**: Django 5.2
- **Frontend**: Bootstrap 5.3
- **Database**: SQLite (default)
- **Language**: Python 3.12
- **Template Engine**: Django Templates

---
````

## 🚀 Getting Started

Follow these steps to set up the project locally:


### 1. Clone the Repository

```bash
git clone https://github.com/SANK-0311/Django-FoodApp.git
cd Django-FoodApp
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

> If `requirements.txt` doesn't exist yet, generate it:
>
> ```bash
> pip freeze > requirements.txt
> ```

### 4. Run Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser (for admin access)

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

Now visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📁 Folder Structure

```
Django-FoodApp/
├── food/               # App for food item logic
├── users/              # Handles authentication and profile
├── templates/          # Global templates folder
├── static/             # CSS and static files
├── db.sqlite3          # Default database
├── manage.py
├── README.md
```

---
---

## ✍️ Author

Made with ❤️ by **SANTHOSH KUMAR**
[GitHub Profile](https://github.com/SANK-0311)

> If you like this project, consider giving it a ⭐ on GitHub!
