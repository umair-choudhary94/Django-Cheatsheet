# Django Cheat Sheet 🚀

Here's the entire Django Cheat Sheet in one place for easy copying:

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install django
```

## Creating Project

```python
django-admin startproject projectname
```
## Create a Django App

```python
python manage.py startapp appname
```

## Run Development Server

```python
python manage.py runserver
```

## Create Superuser

```python
python manage.py createsuperuser
```

## Create Migrations

```python
python manage.py makemigrations
```
## Apply Migrations

```python
python manage.py migrate
```
## Django Shell (Interactive Console)
```python
python manage.py shell
```
## Start Django Project with Virtual Environment

```python
python3 -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate  # On Windows
```
## Django Models

```python
class MyModel(models.Model):
    field_name = models.CharField(max_length=255)

```
## Django Views

```python
from django.shortcuts import render

def my_view(request):
    return render(request, 'template_name.html')

```
## Django URLs

```python
from django.urls import path
from . import views

urlpatterns = [
    path('my-view/', views.my_view, name='my-view'),
]

```
## Django Templates

```python
<!DOCTYPE html>
<html>
<head>
    <title>{{ page_title }}</title>
</head>
<body>
    <h1>{{ heading }}</h1>
</body>
</html>

```
## Static Files

```python
STATIC_URL = '/static/'
```

## Django Forms

```python
class MyForm(forms.Form):
    my_field = forms.CharField()

```
## Django Admin

```python
from django.contrib import admin
from .models import MyModel

admin.site.register(MyModel)

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Regards : Engr Umair
## Follow Me On Facebook
More cheat sheets on the way!

[Facebook](https://www.facebook.com/umair.choudhary.9494/)