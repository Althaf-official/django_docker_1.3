
on windows to create virtual environment
$python -m pipenv install django==2.2.4 gunicorn

6. Test Gunicorn
$pip install uvicorn gunicorn
$uvicorn cfehome.wsgi:application --host 127.0.0.1 --port 80 --reload
