<h1 align="center">Django TODO <a href="https://github.com/juls-teacher/todo" target="_blank">app</a> 
<h3 align="center">Creating a website with adding information to the database</h3>

![ScreenShot](https://raw.github.com/juls-teacher/todo/master/img_1.png)

Project Structure:
  <h4>todo/ - project root folder, repository</h4>
  <h4>manage.py - Django app</h4>
  <h4>.venv/ - virtual environment</h4>

Commands for Creating a Project Structure

    $ cd projects/
    $ mkdir todo/
    $ cd todo/


Сreate a venv

    $ sudo apt install python3-virtualenv

    $ virtualenv -p python3 --prompt=todo .venv/

    $ python3 -m venv --prompt=todo .venv/

    $ source .venv/bin/activate

    $ sudo su postgres

    $ psql

    $ CREATE USER 'user' WITH PASSWORD 'password' CREATEDB; $ CREATE DATABASE todo OWNER 'owner';

Creating base tables in the database

    $ cd projects/todo/

    $ python manage.py migrate

Creating a system user

    $ python manage.py createsuperuser

Starting a local server

    $ python manage.py runserver


Author: Julia Yurchuk 

Link: https://github.com/juls-teacher/todo