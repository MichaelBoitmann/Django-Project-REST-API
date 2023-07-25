# Profiles REST API Project doce.

```bash
$ vagrant ssh
```
```bash
$ cd /vagrant/
```
```bash
$ source ~/env/bin/activate
```
```bash
$ pip install -r requirements.txt
```
```bash
$ django-admin.py startproject profiles_project .
```
```bash
$ python manage.py startapp profiles_api
```
```bash
$ python manage.py runserver 0.0.0.0:8000
```
```bash
$ python manage.py makemigrations profiles_api
```
```bash
$ python manage.py migrate
```
```bash
$ python manage.py createsuperuser
```