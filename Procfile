release: cd frontend && npm install
release: cd frontend && npm run build
release: cd backend && python manage.py migrate
web: cd backend && gunicorn backend.wsgi --log-file -
