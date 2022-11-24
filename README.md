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

## Cinema Manager interface
![image](https://user-images.githubusercontent.com/57757171/203784050-fb802fcf-e344-48ed-97f4-650a4545720b.png)

## Manage films interface
![image](https://user-images.githubusercontent.com/57757171/203784192-14a42a1b-f13b-49ad-9373-6c477bea1a4e.png)

## Add a screen interface
![image](https://user-images.githubusercontent.com/57757171/203784288-15cb403f-44e1-4deb-afee-c8f4cf829a1b.png)

## Add showing interface
![image](https://user-images.githubusercontent.com/57757171/203784386-de739812-459a-4815-8249-b6edc8832ff2.png)

## Change ticket prices interface
![image](https://user-images.githubusercontent.com/57757171/203784449-1c2ee7e5-8d2a-424c-bc3e-5df2974a9d49.png)

## Add Club membership interface
![image](https://user-images.githubusercontent.com/57757171/203784524-af25c13d-474a-4a8d-998a-5fa3a49324a2.png)

## Add Club representative interface
![image](https://user-images.githubusercontent.com/57757171/203784588-75884c50-0b99-4d5d-8d7b-7c97e49c9403.png)

## Manage Cancellations interface
![image](https://user-images.githubusercontent.com/57757171/203784723-59cb7a47-6469-4550-98ca-730688acb61c.png)


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
