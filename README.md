# insta-lite

# Description

This is a clone of the website for the popular photo app Instagram .

# Author
Adlight Akinyi

# Set-up/installation requirements
git clone https://github.com/AdlightAkinyi/insta-lite.git

cd insta-lite

python3 -m venv virtual

source virtual/bin/activate 

pip install -r requirements.txt 

# setup database
python manage.py makemigrations instagram

python manage.py migrate 

# Running the app

python3 manage.py runserver

# Testing the app

python3 manage.py test 

Open the application on your browser 127.0.0.1:8000.

# Technologies used
python3.8

Django

Heroku

# Support/Contact details
adlightakinyi1@gmail.com

# licence
AdlightAkinyi/insta-lite is licensed under the

MIT License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
