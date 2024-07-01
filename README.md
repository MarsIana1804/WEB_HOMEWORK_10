pip install scraper, django, sqlalchemy_utils

python 01_export_collection.py
python 02_create_database.py

# create django project
django-admin startproject quotes_project
cd quotes_project

# create django App
python manage.py startapp quotes

python3 manage.py makemigrations
python3 manage.py migrate

# create admin user
python3 manage.py createsuperuser

python3 03_fill_out_tables.py


python3 manage.py runserver

