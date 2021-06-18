# Mcq-Web-App
online Quiz for school students 


INSTRUCTIONS

1.Installations
Make sure to have python version3 installed on pc or laptop.
clone repository
https://github.com/Vakity-siri2345/Mcq-Web-App

2.Installing dependencies
it will install all required dependencies in the project.
   pip install -r requirements.txt

3.Migrations
To run migrations
   py manage.py makemigrations
   py manage.py migrate

4.(i)Create superuser
To create super user run.
   py manage.py createsuperuser
After running this command it will asks username, password.You can access admin panel from
    http://127.0.0.1.8000/admin/

(ii)Running locally
To run localhost.It will run on port 8000 by default.
    py manage.py runserver
