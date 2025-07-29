# Django

## Intro


## Virtual Environment
### 1. Install pipenv 
* **pip install --user pipenv**

### 2. Install Django with pipenv
* **python3 -m pipenv install "Django~=5.1.0" (macOS)**
* virtual env typically stored in (macOS): ~/.local/share/virtualenvs/

### 3. Activate the virtual env
* **python3 -m pipenv shell**
* *python3 -m pip list* (check versions)
* *exit* (to deactivate virtual env)


## Django Project

### 1. Create a Django project named “UniHaven” with an app called “accommo”
* **django-admin startproject UniHaven .** (current folder ".")

### 2. Create an app called “accommo”
* **python manage.py startapp accommo**

**Config/app root:**
- UniHaven
  -> ...
- accommo
  -> ...
- manage.py
- Pipfile
- Pipfile.lock

### 3. Register app in settings.py

### 4. Commonly used commands:
- **python3 manage.py makemigrations accommo** 
- **python3 manage.py migrate** 
- **python3 manage.py createsuperuser**
- **python3 manage.py runserver**
- **python3 manage.py shell** (QuerySet API)
