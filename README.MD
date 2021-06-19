# Virtual environment einrichten
python3 -m venv env

# Virtual environment aktivieren
source env/bin/activate

# Django installieren
pip install django

# Django projekt start
django-admin startproject umfrageseite

# run server
# cd portfolio-project
source ../env/bin/activate
python manage.py runserver

# create app
python manage.py startapp polls 

# restrucurize data base
python3 manage.py makemigrations
python manage.py migrate

python3 manage.py createsuperuser

python manage.py shell

git add -A
git commit -m "Add apps"