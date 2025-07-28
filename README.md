# Django


### 1. Install pipenv (virtual environment)
**pip install --user pipenv**

### 2. Install Django with pipenv
**python3 -m pipenv install "Django~=5.1.0" (macOS)**
* virtual env typically stored in (macOS): ~/.local/share/virtualenvs/

### 3. Activate the virtual env
**python3 -m pipenv shell**
* check versions: *python3 -m pip list*
* to deactivate virtual env: *exit*

### 4. Create a Django project named “UniHaven” with an app called “accommo”
**django-admin startproject UniHaven .** (current folder ".")
**python manage.py startapp accommo**

Config/app root:
- UniHaven
  -> ...
- accommo
  -> ...
- manage.py
- Pipfile
- Pipfile.lock

### 5. Register app in settings



chmod +x manage.py 
python3 manage.py makemigrations accommo
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
