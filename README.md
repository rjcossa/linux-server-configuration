# Linux Server Deployment Project

This is the last project in the Udacity Nanodegree that entails the deployment of a Linux Web Server to a cloud provider

## Host Details

* IP ADDRESS: 18.195.55.88
* SSH Port: 2200
* URL: http://18.195.55.88/


## Software Installed

- Python2
- Apache2
- Apache Mod WSGI Module
- Pip
- PostgreSQL


## Configuration Made:

- Configure SSH to use Port 2200
- Configure UFW to accept only SSH (Port 2022), HTTP (Port 80) and NTP (Port 123) Traffic
- Configure PostgreSQL with a `catalog` user that has permissions on the catalog_schema
- Create a `catalog` local user for `ident` database authentication
- Ensure that the PostgreSQL database is bound to 127.0.0.1 so that remote connections are not allowed
- Configure the Flask app to work with WSGI
- Download the Google Client Secret to use with the Flask Application
- Create the grader User
- Add a grader suders.d file
- Configure the Python application to use the PostgreSQL database (Previously SQLite)
- Test the Python Application through port 80


## Additional Python Modules Installed:

- Google API Client
- Requests
- Flask
- SqlAlchemy
- PsycoPg2
