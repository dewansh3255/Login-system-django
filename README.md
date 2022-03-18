
# Login System in django

A simple project developed with the help of django web framework using python. In this webapp user will be able to register himself, and can login only if he completes the verification procedure, sent on the provided email address.

## Getting Started
- install the prerequisites
- run the server
- admin credential
    - username : admin
    - password : root123
- demo users
    - username1 : demo-user
    - username2 : test-user
    - password : user@123 (same for both users)

## Prerequisites
You can install the Prerequisites by running the command:
```bash
pip install -r requirements.txt
```

## Features

- User will be able to register in the website
- User will receive a confermation email in order to activate their account


## Utility Commands

Install virtual environment

```bash
pip install virtualenv
```
Create a virtual environment

```bash
virtualenv name_of_virtualenv
```
Activate the virtual environment(windows)

```bash
name_of_virtualenv\Scripts\activate
```
Activate the virtual environment(mac)

```bash
source name_of_virtualenv\Scripts\activate
```
Create Django project

```bash
django-admin startproject project_name
```
Create Django app

```bash
python manage.py startapp app_name
```
Create a super user(admin)

```bash
python manage.py createsuperuser
```
