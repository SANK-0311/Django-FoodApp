# 🍴 Django FoodApp

A simple and elegant Django web application that allows users to register, login, and manage food items with full CRUD functionality. Built using Django and Bootstrap 5 for a modern and responsive UI.

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
> /Screenshots/HomePage.png


---

## 🛠️ Tech Stack

- **Backend**: Django 5.2
- **Frontend**: Bootstrap 5.3
- **Database**: SQLite (default)
- **Language**: Python 3.12
- **Template Engine**: Django Templates

---

## 🚀 Getting Started

Follow these instructions to set up the project locally:

### Clone the repository by using the Below link

git clone https://github.com/SANK-0311/Django-FoodApp.git



### File Structure
mysite/
├── food/               # Main app for item logic
│   ├── models.py       # Item model
│   ├── views.py        # All views (class-based & function-based)
│   ├── urls.py         # URL routing
│   ├── templates/food/ # Templates (index, detail, forms)
├── users/              # Authentication & profile logic
│   ├── models.py       # Profile model (linked to User)
│   ├── views.py        # Register/login/logout
│   ├── templates/users/# Auth templates
├── static/             # CSS/static files
├── db.sqlite3          # SQLite database
├── manage.py


Once, Cloned the project... open the Intergrated Terminal and run the below command line to start the project

python manage.py runserver