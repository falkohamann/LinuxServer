Falko Hamanns Linux Server
=======================
Project: Linux Server Configuration


What Is This?
-------------

I have configured and Ubuntu Webserver.
It runs one of my earlier applications, the Item catalog.


How to access the server?
-----------------------

public ip: 18.195.229.119
host name: http://ec2-18-195-229-119.eu-central-1.compute.amazonaws.com
url to acces the item catalog: http://ec2-18-195-229-119.eu-central-1.compute.amazonaws.com/catalog

The server can be accessed by SSH on port 2200 by user grader.
The needed private key will be found in this repository.

filename for private key of user grader: priv_key.ppk


Which software is used?
-----------------------

The server runs with Apache 2 and the wsgi plugin.
Postgresql serves as database.


Database
-----------------------

The Database runs by Postgresql.
To access the catalog database use user catalog and password catalog.
