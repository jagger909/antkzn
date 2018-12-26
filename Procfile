web: gunicorn config.wsgi:application
worker: celery worker --app=antkzn.taskapp --loglevel=info
