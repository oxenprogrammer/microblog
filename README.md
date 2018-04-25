Microblog

The Microblog Application is one that allows users to create accounts that can be used to authenciate them into the system. This version of the application only contains minimal designs for the User Interface and mimnal functionality. It is still a work in progress

Features
The application has a couple of expected features as listed below:-

A user is able to Register and get an account in the app
A user is able to Login into the app using their credentials already supplied
A user is able to request for a password reset that they can reset through an email sent to them
A user is able to create posts,and send messages to other users
A user is able to follow and by followed our users.
A user is able to see posts of users the follow.
A user is also able to create, edit, update and delete Recipe Items


Setup locally or if you wish to contribute
Create the virtual environment and activate it


Then install all the required dependencies by running
pip install -r requirements.txt

activate flask env, 
export FLASK_APP=medium

Run the app
flask run

To now view the application head over to

http://l27.0.0.1:5000

on heroku https://emmisteel.herokuapp.com 
NB: remember to click remember me when logging in as there is still a bug in there. everything is still a work in progress