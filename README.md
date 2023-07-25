# Profiles REST API Project doce.

'''
$ vagrant ssh
'''
'''
$ cd /vagrant/
'''
$ source ~/env/bin/activate
$ pip install -r requirements.txt
$ django-admin.py startproject profiles_project .
$ python manage.py startapp profiles_api
$ python manage.py runserver 0.0.0.0:8000
$ python manage.py makemigrations profiles_api
$ python manage.py migrate
$ python manage.py createsuperuser