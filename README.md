# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
admin.py

from django.contrib import admin
from .models import employee
admin.site.register(employee)

models.py

from django.db import models
class employee(models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=20)
    dept=models.CharField(max_length=20)
    salary=models.FloatField()

```

## OUTPUT

![Screenshot (164)](https://github.com/SYEDADILBASHA1/ORM/assets/134796157/9e4a7d26-c15b-4af5-99b8-6d31c3a454ac)


## RESULT
Thus the program for creating a database using ORM hass been executed successfully
