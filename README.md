# Linux-server-configuration
The aim of this project is to learn and practice how to configure an Apache2 web server on a cloud-based Ubuntu server. The web content utlimately deployed consists of an application written in Python, with a PostgreSQL relational database back-end. This applicaiton was created earlier as part of Udacity Full Stack Nanodegree course.  

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
The project was developed following the study materials and help resources of [Udacity Full Stack Developer Nanodegree](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).

I also referred to the documentation of [Apache2 Web Server](https://httpd.apache.org/), [Ubuntu Help Pages](http://manpages.ubuntu.com/manpages/xenial/en/man5/sshd_config.5.html), [Digital Ocean tutorials](https://www.digitalocean.com/community/tutorials/) and [Stack Overflow](https://stackoverflow.com/) clarifications. 
