# **E-commerce**

A web application built in Django for purchasing products online.


## **Project Setup**

Clone the repository:

````
$ git clone https://github.com/gocardless/sample-django-app.git
$ git pull
$ git checkout -b [name_of_your_new_branch]
````

Create virtual environment:

````
$ virtualenv venv
$ source venv/bin/activate
````


You will see in front of the prompt that the virtual environment (venv) has been activated.  

Install the dependencies:

````
$ pip install -r requirements.txt
````

## **Setup a database**

Configure Database settings in settings.py folder as suggested in below documentation:

````
https://docs.djangoproject.com/en/4.0/ref/settings/#databases
````

Create a .env file in the project folder.
You can find .env.example file for your reference.

Execute below command to create migrations and register models in the database:

````
python manage.py makemigrations
python manage.py migrate
````

## **Starting the web server**

Run the development server using below command:

````
python manage.py runserver
````

Navigate to http://127.0.0.1:8000/ 

## Setup the Products module 

Run the below command to populate the database with products:

````
 python manage.py loaddata products.json
 ````












