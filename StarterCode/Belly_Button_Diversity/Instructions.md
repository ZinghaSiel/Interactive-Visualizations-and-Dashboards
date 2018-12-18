These files need to be in thesame folder as the app.py file

1. requirements.txt contains all the dependencies that are used in the application:

pip freeze > requirements.txt

2. Procfile

web: gunicorn app:app

3. run.sh

FLASK_APP=app.py flask run

4. runtime.txt (or create python environment)

python-3.6.2