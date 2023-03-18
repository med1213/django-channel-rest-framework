# Live Data (Real-time data) in Django using Django Channels

## Technology Stack
Backend: Django, Django Rest Framework, Django channels, Redis<br />
Frontend: HTML


## To run the project
Prerequisites: Python3, Redis Server, virutalenv

## Plugins Used:
Django: https://docs.djangoproject.com/en/4.0/topics/install/#installing-official-release<br />
DRF: https://www.django-rest-framework.org/<br />
Redis: https://redis.io/docs/getting-started/installation/install-redis-on-linux/<br />
Django Channels: https://channels.readthedocs.io/en/stable/index.html<br />
DRF Channels: https://djangochannelsrestframework.readthedocs.io/en/latest/<br />
Redis-Server: https://pypi.org/project/redis-server/

## Basic Settings
You’ll have to make the following creations to your your .env file

    DB_NAME=your_database_name
    DB_USR=your_user_name
    DB_PWD=your_password

## To run the project
1. Checkout the code
2. Create a virtual environment (virutalenv .env)
3. Activate the environment (source .env/bin/activate)
4. Install all the packages (pip install -r requirements.txt)
5. Migrate (python manage.py migrate)
6. Create a superuser (python manage.py createsuperuser) <br />
   Fill in all the details on the terminal to create the superuser
7. Run the backend server (python manage.py runserver)
8. Visit the server link (http://localhost:8000/)

# django-channel-rest-framework
