# Health Connect
> Manage the entire infrastructure of a hospital with one application

![logo](./static/images/medlogo.png)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)


## General Information
Our hospital management web application, Health Connect, aims to address the challenges faced by healthcare organizations in efficiently managing their operations. By streamlining various tasks such as patient handling, receptionist duties, doctor management, 
and administrative functions, Health Connect empowers healthcare providers and administrative staff to enhance patient care and optimize organizational effectiveness.


## Technologies Used
- Django 
- Bootstrap 4
- Postgresql


## Features
- Patient Database and Login
- Patient Medical History  
- Prescription Management
- Appointement Management
- Hospital Accounting
- Invoicing
- Doctor Database and Login
- Receptionist Database and Login

## Setup
### Step 1
Installing Django
`pip install django`
### Step 2
Installing Django crispy forms  
`pip install django-crispy-forms`
### Step 3
Installing crispy bootstrap4  
`pip install crispy_bootstrap4`
### Step 4
Installing Psycopg (PostgreSQL adapter for Python)  
`pip install psycopg`
Add these lines in settings.py file:  
 &nbsp; DATABASES = {  
    &nbsp; &nbsp; 'default': {  
    &nbsp; &nbsp; &nbsp; &nbsp;     'ENGINE': 'django.db.backends.postgresql_psycopg2',  
    &nbsp; &nbsp; &nbsp; &nbsp;     'NAME': 'telemedecine',  
    &nbsp; &nbsp; &nbsp; &nbsp;     'USER': 'postgres',  
     &nbsp; &nbsp; &nbsp; &nbsp;    'PASSWORD': 'root',  
    &nbsp; &nbsp; &nbsp; &nbsp;     'HOST': 'localhost',  
      &nbsp; &nbsp; &nbsp; &nbsp;   'PORT': '5432'  
 &nbsp; &nbsp;    }  
 &nbsp;}   

### Step 5
Installing Psycopg (PostgreSQL adapter for Python) and setting it up with Django  
`python manage.py makemigrations`  
`python manage.py migrate`


## Usage
Running the Website  

`python manage.py runserver`


## Project Status
Project is: _in progress_ .


## Room for Improvement
- Completing the Invoice functionnality (adding support for payment systems)
- Adding an HR role

## Contact
Created by:
- ilyaskotbi02@gmail.com
- aminekebir17@gmail.com  
- hichamzamranismb@gmail.com
- mazianewassim@gmail.com  
Feel free to contact us!
