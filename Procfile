release: python manage.py makmigrations --no-input
release: python manage.py migrate --no-input
release: python manage.py collectstatic --no-input

web: gunicorn linkedfin_backend.wsgi