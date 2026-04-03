# Production

# See Claude "Heroku TabbyCat installation troubleshooting"

web: gunicorn tabbycat.wsgi --chdir tabbycat --log-file -
worker: python tabbycat/manage.py runworker notifications adjallocation venues
