# django_16-30
python programming
1. python -m venv venv (windows - py / linux (arch base) - python / mac and debian linux - python3)
2. .\venv\Scripts\activate on windows and source ./venv/bin/activate mac, linux
3. python -m pip install --upgrade pip
4. pip install django
5. django-admin startproject core(any name)
6. cd core
7. python manage.py startapp main(any name)
8. add main in settings INSTALLED_APPS
9. create urls.py in main folder
10. connect core/urls.py in to main/urls.py
11. create python function in views.py and show this data in local host
12. add new page url in main/urls.py
13. python manage.py makemigrations
14. python manage.py migrate
15. python manage.py createsuperuser
        - name
        - email(not required)
        - password1
        - password2
16. python manage.py runserver
