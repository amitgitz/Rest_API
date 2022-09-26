What is Rest Framework 
Reoresentational State Transfer (Rest ) is a internet protocol that describes a uniform interface between physically seprate component and oftern across the internet in a client-server architecture.

**1. Django Project Setup**
Create the Virtual Environment
python -m venv venv
Then activate that environment
venv\Scripts\activate
Then install DjangoRestFramework in that environment
pip install djangorestframework
Then Create the Project Folder
django-admin startproject MyProject
Move to the MyProject Directory
cd MyProject
Migrate the Project
python manage.py migrate
Run the Project on the Local Machine
python manage.py runserver

**** Important****
Create the APIs App
python manage.py startapp RestAPIs

Create SuperUser
python manage.py createsuperuser
Username : ______________(Put as per your preference)
Email Address : ___________( Skip or Put)
Password : _____________(Put as per your preference)

Superuser Created Sucessfully.
Now you can login to the web admin panel




