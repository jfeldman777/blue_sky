release: python manage.py migrate
         python manage.py collectstatic 
web: gunicorn blue_sky.wsgi
