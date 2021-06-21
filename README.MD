# create virtual environment
python3 -m venv env

# activate virtual environment 
source ../env/bin/activate

# install Django 
pip install django

# Django create project
django-admin startproject <projectname>

# run python server
source ../env/bin/activate
python manage.py runserver

# create python app
python manage.py startapp <appname>

# restrucurize python data base
python3 manage.py makemigrations
python manage.py migrate

# create python data base admin
python3 manage.py createsuperuser

python manage.py shell

# git version updates
git add -A
git commit -m "Lection 40 Bootstrap"