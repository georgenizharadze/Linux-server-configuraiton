# Linux-server-configuration
The aim of this project is to learn and practice how to configure an Apache2 web server on a cloud-based Ubuntu server. The web content utlimately deployed consists or an application written in Python and a PostgreSQL relational database back-end. This applicaiton was created earlier as part of Udacity Full Stack Nanodegree course.  

## IP address and SSH port
IP address is: 3.8.219.65

SSH port is: 2200

The code is in `/var/www/readings-app` folder. 

## Software installed and configuration changes made
I insalled Apache 2, mod_wsgi and PostgreSQL packages. I also installed the relevant Python packages such as Flask, SQLAlchemy, requests, oauth2client, etc. 

I added user `grader` to my Ubuntu instance and granted a sudoer status to it. I enabled access via public-privat keys and disabled password-based authentication. 

I created a user for PostgreSQL database per guidance provided by Udacity. 

I created an Apache config file for my application, as well as a wsgi file. 

## Third party resources used to complete the project
