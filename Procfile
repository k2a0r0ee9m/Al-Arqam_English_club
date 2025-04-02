web: gunicorn English_club.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn English_club.wsgi