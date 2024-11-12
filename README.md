# DjangoProjectStart

Open folder where project will be on pycharm ide or VS Code


Create a virtual environment

    python -m venv envname
    
if environment is not active;

    envname/Scripts/activate  
    pip install --upgrade pip
    pip install django
    django-admin startproject '[project name]' .   (dont forget the dot)
    python manage.py startapp 'appname'
    
On the terminal;

      python manage.py createsuperuser
      python manage.py runserver
      python manage.py makemigrations
      python manage.py migrate
