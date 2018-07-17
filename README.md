# django-bulma-admin
A Django Admin interface implementing the Bulma CSS pack: https://bulma.io

## Installation 
Add the "DjangoAdminBulma" directory to your existing project. In settings.py add:

```
INSTALLED_APPS = [
    ...
    'DjangoAdminBulma',
    'django.contrib.admin',
    ...
]
```
**Make sure** you add the app name **before** ```'django.contrib.admin```!!!

## Logo
If you want to use your own logo in the admin panel, simply upload the file "logo.png" to the directory "static/base/img/".