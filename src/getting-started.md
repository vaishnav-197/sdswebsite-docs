# Getting Started

## Quick Start

* fork the project to your profile
  * clone the project from your profile
  * install virualenv in your local machine using the command

            sudo apt-get install python3-dev python3-pip python3-virtualenv
            pip3 install virtualenv
  * make virtualenv inside the repo folder( dont forget dot in command)

             virtualenv -p python3 env
            . env/bin/activate
  * install django 2.1.3

            pip3 install -r requirements.txt
  * run the django dev server

             python3 manage.py runserver
  * cancel the operation by pressing Ctrl+C or Ctrl+Z

  * makemigrations using

            python3 manage.py makemigrations
            python3 manage.py migrate

  * make a superuser

            python3 manage.py createsuperuser

  * run the django dev server

            python3 manage.py runserver
