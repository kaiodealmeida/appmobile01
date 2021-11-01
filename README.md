# Introduction
A simple Mobile APP using Flutter as frontend and Django REST as backend

## How to install:

1. Install a WSGI (we recommended to use Gunicorn), and a http proxy service (we recommended to use Nginx).

2. Run on a terminal in the project folder to instaLL all dependencies ``` pip install -r requirements.txt ```

3. Rum on a terminal, in the same folder  ``` python manage.py migrate  ``` 

4. Test the application with command  ``` python manage.py runserver  ``` 

5. If you're using Ubuntu, run  ``` sudo ufw allow 8000 ``` to allow access to port 8000.

6. If everythings ok, you can configure Nginx and Gunicorn to proceed.

7. Don't forget to see Django doc to make all securitys steps for deploy.

