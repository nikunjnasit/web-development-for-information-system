release: python manage.py migrate
web: gunicorn banking_system.wsgi --log-file -
worker: python manage.py celery worker --loglevel=info