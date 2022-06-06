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
