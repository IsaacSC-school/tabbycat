# Production

# See Claude "Heroku TabbyCat installation troubleshooting"

release: python tabbycat/manage.py collectstatic --noinput && python tabbycat/manage.py migrate
web: gunicorn tabbycat.wsgi --chdir tabbycat --log-file -
worker: python tabbycat/manage.py runworker notifications adjallocation venues
