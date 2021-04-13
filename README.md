# simple-django-blog

create a virtual environment
```python3 -m venv environment_name
```

activate the environment
```. /environment_name/bin/activate
```
install the requirements.txt

create a user and database for postgresql
```su postgres
createuser -dP blog
createdb -E utf8 -U blog blog
```
Edit your database settings on settings.py file and add the databasename, username and password you created.

Add your email details in the settings.py file 

run 
```python3 manage.py makemigrations
python3 manage.py migrate
```
start your server:
```python3 manage.py runserver 
```
