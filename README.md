# Local-Server-Test

We will be setting up a local server on my machine and create a complete Python/ Apache/ PostgreSQL environment

Step 1: Create local host on my machine
Download MAMP
https://www.mamp.info/en/downloads/

Testing all elements will occur in the local environment.
Later, we will be deploying code pushes using Heroku PaaS.

This tutorial for setting up a Django project can be found here: 
http://www.marinamele.com/taskbuster-django-tutorial

This task list is the topics from the above tutorial

Part I – Working environment and start a Django Project

Building your Working environment
Install Django 1.8
Working directory and Sublime Text (Pycharm?)
Obey the Testing Goat
Create a Django project
Start a development server

Part II – Settings files and Version control

Virtual environments and requirements files
Different settings.py for each enviroment
Production settings.py – Debug False
Django security and the Secret Key
Initialize a Git repository and Commit
Upload your project into Bitbucket

Part III – Create a Home Page with TDD, Staticfiles and Templates settings
Static Files Settings
Templates Settings
Initializr: HTML5 Boilerplate and Twitter Bootstrap
Home Page with TDD – Tests first
Home Page with TDD – Code next
Commit again to your local repository and Bitbucket
Part IV – Template Inheritance, Website files and Testing with coverage

Template Inheritance
Robots.txt and humans.txt files
The favico.ico image
Testing with Coverage
Part V – Internationalization and Localization. Languages and Time zones

Internationalization – Settings
Internationalization – Urls
Internationalization – Templates
Internationalization – Translation
Localization
Time Zones

Part VI – Documenting the TaskBuster Django Boilerplate
Install and configure Sphinx
Documenting the TaskBuster Django Project Boilerplate
Upload your project on GitHub
Upload your Docs on ReadTheDocs
TaskBuster Django Project Boilerplate

Part VII.a – Install and Configure PostgreSQL
Install PostgreSQL
Create a PostgreSQL Database
Install the PostgreSQL Django adapter, psycopg2
Configure the Django Database Settings
Part VII.b – Install and Configure MySQL

Part VIII – User Authentication with a Google Account using Django Allauth
Define what we expect and write a Test
Install django-allauth
Settings File
Urls
Database migrations
Sites configuration
Google App registration
Allauth Django configuration
Testing the user flow
Part VIII.b – User Authentication with Twitter using Django Allauth

Test First! Test First!
Configure Allauth
Create a Twitter Application
Part IX – Model creation, OneToOne relations, signals and the Django Admin

UML Diagram of the TaskManager app
Create the TaskManager app
Profile Model: OneToOne relationship with the User Model
Django Signals: create a Profile instance when a new user is created
The Django Admin for the Profile Model
Part X – Model creation, ForeignKey relations, testing and the Django Admin

UML Diagram Revision
The Project Model: Foreign Key Relationships and custom validators
Tests for the Project Model
Django Admin for the Project Model: custom list display and Model Inline
