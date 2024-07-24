# django-add-extract-data

## Links
- https://www.photondesigner.com/articles/loaddata-dumpdata

## Commands
- pip install django pyyaml python_dotenv
- django-admin startproject core .
- python manage.py startapp sim
- python manage.py makemigrations
- python manage.py migrate
- python manage.py loaddata sim product_data.yaml
- python manage.py loaddata product_data.yaml
- python manage.py createsuperuser
- python manage.py runserver
- python manage.py dumpdata sim.product --natural-foreign --exclude=contenttypes --exclude=auth.permission > product_data1.yaml
- cat product_data1.yaml
