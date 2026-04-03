# Production

# See ChatGPT "TabbyCat Deployment on Heroku"

web: gunicorn tabbycat.wsgi --log-file -
worker: python manage.py runworker notifications adjallocation venues
