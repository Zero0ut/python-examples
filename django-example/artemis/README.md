### Creating a project

```
django-admin startproject mysite
```

### Start development server

```
python manage.py runserver
```

### Create App

To create your app, make sure you’re in the same directory as manage.py and type this command:

```
python manage.py startapp polls
```


### Create Database

The migrate command looks at the INSTALLED_APPS setting and creates any necessary database tables according to the database settings in your mysite/settings.py file and the database migrations shipped with the app

```
python manage.py migrate
```

References:
https://docs.djangoproject.com/en/3.1/intro/tutorial01/
