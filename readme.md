# Udacity FSND Linux Server Configuration Project

## Description
Configure an Amazon Lightsail Linux server to host the catalog application

## The IP address and SSH port
Hostname: cbaines.org
IP Address: 18.222.121.126
SSH Port: 2200

## The complete URL to your hosted web application.

http://cbaines.org

## A summary of software you installed and configuration changes made

Software Installed:
Apache2
Apache mod-wsgi
Postgres
PIP
PIP Packages for my catalog application (Flask, SQLAlchemy, HTTPAuth, etc)


Configuration Changes:
Update SSH port to 2200
Update Amazon firewall to allow required ports (2200, 80, 123)
Update UFW to allow required ports (2200, 80, 123)
Create user grader
Setup grader ability to use sudo
Create SSH key pair
Setup grader to use SSH key-pair for login
Confirm only SSH keypair login is allowed for SSH
Use git to install catalog application from my github
Install Postgres / setup user catalog / add permissions for user catalog

Application Changes:
Run lotsofitems.py to establish catalog DB
Add mod-wsgi configurations for catalog app
Add hostname to FB/Google auth configurations and json files
Edit code for Postgres SQL user catalog and local DB server

## Third-party resources made use of to complete this project
Udacity Forums
Installing WSGI - https://devops.profitbricks.com/tutorials/install-and-configure-mod_wsgi-on-ubuntu-1604-1/
Updating Virtual Host for Apache 2.4+ - http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/
Postgres Configuration - http://docs.sqlalchemy.org/en/latest/core/engines.html


## Author
Chris Baines