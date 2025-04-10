# 🧑‍🎓 Student Registration App (Django + PostgreSQL)

This is a basic **Student Registration Web Application** built using the **Django framework** and **PostgreSQL** as the database.  
The app allows users to register students with their name, age, and class, and view all registered students in a clean HTML template.

---

## 📌  How to build this

- ✅ Setup Django project
- ✅ Configure PostgreSQL as the database in student_project/student_project/settings.py and configure the database like below
- ## Configure PostgreSQL in Django (settings.py)
      DATABASES = {
          'default': {
              'ENGINE': 'django.db.backends.postgresql',
              'NAME': 'student_db',         # Your database name
              'USER': 'postgres',           # Your PostgreSQL username
              'PASSWORD': 'yourpassword',   # Your PostgreSQL password
              'HOST': 'localhost',
              'PORT': '5432',
          }
      }  
- ✅ Create a `Student` model
- ✅ Build student registration form (name, age, class)
- ✅ Create views and URL routing
- ✅ Develop templates using HTML
- ✅ Display list of registered students

---

## 🛠️ Prerequisites

Make sure the following are installed:

- [Python](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/)
- [PostgreSQL](https://www.postgresql.org/download/)
- Django (`pip install django`)
- psycopg2 (`pip install psycopg2` or `psycopg2-binary`)

---

## ⚙️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/django-student-registration-app.git
cd django-student-registration-app

# 2. Create virtual environment (optional but recommended)
python -m venv venv
# On Windows: venv\Scripts\activate


# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure your PostgreSQL database in settings.py

# 5 cd student_project
# 5.1 Apply migrations
python manage.py makemigrations
python manage.py migrate

# 6. Run the server
python manage.py runserver


