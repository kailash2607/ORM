# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from Car Inventory Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM



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
from django.db import models

class Movie(models.Model):
    title = models.CharField(max_length=100)
    director = models.CharField(max_length=100)
    release_year = models.IntegerField()
    genre = models.CharField(max_length=50)
    rating = models.FloatField()

    def __str__(self):
        return self.title
```
## ADMIN
```
from django.contrib import admin
from .models import Movie

admin.site.register(Movie)
```


## OUTPUT

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/fde70a4d-35b9-4149-90ca-37cf2744bb5b" />



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
