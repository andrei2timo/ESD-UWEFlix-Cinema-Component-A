# ESD-UWEFlix-Cinema-Component-A

By Andrei-Claudiu Timo

The UWEFlix website is developed using a Django virtual environment, and is intended to replace the existing paper system.

## Installation instructions - Linux
```
$ git clone git@github.com:andrei2timo/ESD-UWEFlix-Cinema-Component-A.git
$ cd Cinema-System-ESD-Component A/UWEFlix_django
$ pip install requirements.txt
$ python3 manage.py makemigrations
$ python3 manage.py migrate
$ python3 manage.py runserver
```
After completing the previous steps, open a web browser and type **http://localhost:8000**

## Installation instructions - Windows

Clone the repository from GitHub:
```
git clone git@github.com:andrei2timo/ESD-UWEFlix-Cinema-Component-A.git
```

Set up a Virtual Environment using: 
```
py -3 -m venv .venv
.venv\scripts\activate
```
... and Install the modules and components required:
```
cd Cinema-System-ESD-Component A/UWEFlix_django
python -m pip install --upgrade pip
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
After completing the previous steps, open a web browser and type **http://localhost:8000**

## Main interface
![image](https://user-images.githubusercontent.com/57757171/203782987-3b954cad-2fd3-4829-8e0d-52e894c25603.png)

## Suporting Documents and Diagrams:
The documents and diagrams can be found in the documents folder.

## Usernames and passwords for test cases:
```
Cinema Manager account:
  Username: cinema_manager
  Password: uweflix1234
  
Student account:
  Username: george.washington
  Password: uweflix123



