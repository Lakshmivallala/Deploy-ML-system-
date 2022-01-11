# Deploy-ML-system-
Experiment - build ML system with REST API
(Incomplete)



[//]: # "Comment"
[//]: # (Comment)
[//]: # (This may be the most platform independent comment)
[comment]: <> (This is a comment, it will not be included)



We try to build an ML system available with _**REST API**_.

Specifications used:
* Ubuntu 19.10
* Python 3.7.3 
* django==2.2.4 
	* (pip3 install django==2.2.4)

A new environment can be created (conda env, virtualenv) but I will not be doing so for this project. If an environemnt is created, it is a requirement to activate the environment everytime you want to restart your project. 

To start a Django project:

> We created a directory/folder named backend where the Django project will be set up. This could be renamed to anything else.

* mkdir backend
* cd backend  <!--- change directory to project folder -->

>server is the name of our Django project that can be renamed.

* django-admin startproject server

>Initiate server

* cd server
* python manage.py runserver 

> If this doesn't work, the below code should fix the issue:

* python manage.py migrate
* python manage.py runserver

#### NOW enter 127.0.0.1:8000 in the web browser to see the Django Welcome site.


Numpy and pandas are used for data manipulation and joblib for saving ML objects.






Based on [pplonski's!](https://github.com/pplonski/my_ml_service) implementation of the same. 
