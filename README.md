# The hood 

## Author
Nicholas Owino 

## Description
A website to keep a user in the know about everything happening within their hood

## Set Up and Installations

### Prerequisites
1. Python version 3.8
2. Django 
3. Pip
4. Virtual Environment(venv)

###  Project Setup
1. Create virtual environment (python3 -m venv virtual)
2. Activate virtual environment (. virtual/bin/activate)
3. Install  all dependencies ( pip install -r requirements.txt)
4. Create database (CREATE DATABASE hood;)
5. Make migrations

    #### Database Migrations
    python3 manage.py make migrations neigh app
    python3 manage.py migrate

6. Run the application
    ### Run 
    python3.8 manage.py runserver

7.  Testing the application
     python3 manage.py test neigh app


### Search functionality
    search by business name 

## Technologies used
    Python 3.8
    Bootstrap
    Django
   
## Live Sute

[View Live Site.](https://nickthehood.herokuapp.com/)

## License

This project is under the [MIT](LICENSE) license.