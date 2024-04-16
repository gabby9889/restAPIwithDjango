# Profiles and Profile Feed CRUD RESTful APIs with Django

## Features
- User Profiles API (CRUD) <br>
- Authentication: Register/Login <br>
- Profile Feed API (posting & viewing - CRUD) <br>
- Authorization: Permissions <br>
- Setup the SQLite database <br>

## Dev Guide
Download and Install Virtual Box and Vagrant:<br>
https://www.virtualbox.org/wiki/Downloads <br>
https://www.vagrantup.com/

Clone the Repo:
```
git clone https://github.com/gabby9889/restAPIwithDjango.git
cd restAPIwithDjango/
git checkout master
```
Start and Provision the VM Environment:
```
vagrant up
```
Connect to the VM using ssh:
```
vagrant ssh
```
```
cd /vagrant
```
Create your own Python local virtual environment:
```
python -m venv ~/env [pathName]
```
Activate your virtual env:
```
source ~/env/bin/activate
```
Install all the dependencies:
```
pip install -r requirements.txt
```
Set up the SQLite Database and Migration:
```
python manage.py makemigrations
python manage.py migrate
```
Run the server!
```
python manage.py runserver 0.0.0.0:8000
```
See your http://localhost:8000/api/


