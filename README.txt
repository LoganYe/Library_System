before run install_flask.sh you should install python-2.7, python-dev, virtualenv(python-virtualenv), mysql-server, mysql-client, libmysqld-dev
python-dev & libmysqld-dev is for flask-mysql
run the install_flask.sh to install all of them

in ./db_data/
first create database
or log in to mysql to create the database using
source create-library-data-for-MySQL.sql

in insert.py , insert_book_loans_and_fine.py and Library_System/app/db_Con.py replace placeholder mysql server password to correspond to mysql server password on your device. 

from the db_data folder , do
1.python insert.py and 
2.python insert_book_loans_and_fine.py 
to run the insert scripts and populate data into tables.

run server:
use ./run.py(ALTERNATIVELY use python run.py)

in a web browser, type localhost:5000
