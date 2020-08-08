Social Media using Django
Social Group website for N users(multiple Users). All visitors can read all the post. 

to create a post or group visitors need to signup and then the can join the existing group or can create there own new group.
After joining a group or creating a group, user can post in the group

Versions-

Python- 3.8 Django- 3 Bootstrap- 4

To run this project in your own computer follow below process:
Note: Some Libraries are required to be installed please check required libraries file and install them
a) To make models and migrate them with applications: 

--> $ python manage.py makemigrations accounts
--> $ python manage.py makemigrations groups
--> $ python manage.py makemigrations posts
--> $ python manage.py migrate


b) To run over a localhost --> $ python manage.py runserver

if the local IP address shows refused to connect --> $ python manage.py runserver 127.0.0.1:8000
