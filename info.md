### Comandos

. venv/bin/activate

------------------------------

pip install django

------------------------------

pip freeze
pip freeze > requirements.txt

---------------------------------------------------------------------------------

ctrl+ship+p > python select interpreter > escolher python venv venv instalado

---------------------------------------------------------------------------------

### Ocultando SECRET_KEY
pip install python-dotenv

---------------------------------------

python django-admin startproject setup .
python manage.py startapp name_app

---------------------------------------

python manage.py makesmigrations

python manage.py migrate

python manage.py runserver

python manage.py collectstatic