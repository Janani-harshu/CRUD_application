## CRUD_application
Building a CRUD application with Flask and SQLAlchemy

## Purpose 
Collecting the sensor data from Edge computing device - The Jetson and publishing the results in web based application - Ngrok

## Requirements 
Execute the follwong commands:
$ sudo apt-get install git python3-virtualenv python3-pip sqlitebrowser
$ git clone https://github.com/macagua/flask-crud-app.git
$ cd ./flask-crud-app
$ virtualenv --python=/usr/bin/python3 venv
$ source ./venv/bin/activate
$ pip3 install -r requirements.txt


## Running 
Execute the following command:

$ python3 bookmanager.py
 * Serving Flask app "bookmanager" (lazy loading)
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://0.0.0.0:8087/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 245-060-649
127.0.0.1 - - [04/Jul/2019 14:21:17] "GET / HTTP/1.1" 200 -


## Reference 
https://www.codementor.io/garethdwyer/building-a-crud-application-with-flask-and-sqlalchemy-dm3wv7yu2
https://docs.sqlalchemy.org/en/latest/orm/tutorial.html
http://flask-sqlalchemy.pocoo.org/2.3/queries/


