web: python mybbt/manage.py collectstatic --noinput; bin/gunicorn_django --workers=1 --bind=0.0.0.0:$PORT mybbt/mybbt/settings.py 
