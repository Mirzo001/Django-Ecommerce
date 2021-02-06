# Django-Ecommerce
Django shop with checkout page.

This is django application that you can add new entries, delete, update and etc.
Admin panel with pretty "Django CMS" 

If you want to run these app in your machine press download .zip file.

***
HOW TO RUN THE DJANGO ECOMMERCE APPLICATION
1. On your command line go to .../django_ecommerce/
2. And run the command: $ python manage.py runserver

***
HOW TO SEE AS AN ADMIN
1. On your command line go to .../django_ecommerce/
2. You firstly add admin superuser as you know on Django.
3. Run the command:  $ python manage.py createsuperuser
4. Enter your admin: "name", admin-password: /------/ and go on.
5. Also you have to migrate your actions in order to save your information on database.
6. Run the commands: 
                      $ python manage.py makemigrations
                      $ python manage.py migrate                     
7. And run the command: $ python manage.py runserver
8. To go to admin page on your browser go to "http://127.0.0.1:8000/admin" or other port that you run
        
        !!! AND THIS ONLY CONNECTED TO SQLITE DATABASE. IF YOUR COMMERCE PROJECT IS FOR WORK, YOU MUST USE SQLSERVER, POSTGRESQL and etc.
        
        *** DEVELOP YOUR PROJECT AND ENJOY!
