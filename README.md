# DjangoCourseBharath

For initial project startup use command:
```
django-admin startproject projectname
```
To create a new app use the command:
```
python manage.py startapp appname
```

In apps the files in including are __init__.py, admin.py, apps.py, models.py, tests.py, views.py. Admin.py is the file which is used to add stuff to the django admin interface. apps.py stores application specific configuration. Models.py is the file which has the database models. tests.py has application specific tests. Views.py is an important file which handles the requests from the user. When you create an app make sure you go to settings.py and add it to the installed_apps list variable. 

In specify a function which returns a specific response in which the user will see.

To configure urls in the project file directory there will be a urls.py file where you can register views using import 
```
from django.urls import path
```
Then use the path function to configure the url.