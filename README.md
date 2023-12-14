# Trio Base

This is a Flask application that is set up and configured to work with a database and nginx. Write kubernetes manifests that will bring all these services up and allow the app to run on port 80.

The flask app needs 2 environment variables:

'MYSQLPW' - The password for the database
'DBNAME' - the database name to connect to

The mysql Dockerfile will require some research of the documentation to launch with correct values.

The database service should be called: 'mysql'
The flask apps service should be called: 'flask-app'
