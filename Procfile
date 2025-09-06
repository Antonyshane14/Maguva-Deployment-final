web: python manage.py migrate && python manage.py create_admin && python manage.py collectstatic --noinput && gunicorn Manguva.wsgi:application --bind 0.0.0.0:$PORT
