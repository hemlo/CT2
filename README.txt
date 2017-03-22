Installation Notes

OS:  linux (ubuntu server)
Apache2 web server
MySql
PHP

https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

Python:
Sqlalchemy:
sudo apt-get install mysql-server
sudo apt-get install mysql-client
sudo apt-get install libmysqlclient15-dev
Second step,install the python-mysqldb:

sudo apt-get install python-mysqldb
//Third step,install the easy_install:

sudo wget http://peak.telecommunity.com/dist/ez_setup.py
sudo python ez_setup.py
//Forth step,install the MySQL-Python:

sudo easy_install MySQL-Python
//Finally,sqlalchemy:

sudo easy_install SQLAlchemy

PySerial:
download tarball from https://pypi.python.org/pypi/pyserial
untar and run:
sudo python setup.py install

TODO:

Database:
#Add/Delete Cow Procedure
#Update Cow Procedure
#Add vaccination data.  Need to figure out how to actually store/display these.  
#Add Users/Logins
#Expand search functionality to include herd and pasture.


RPI:
#Learn more about SQL Alchemy's timeouts, connection pooling, etc., to improve functionality
#Format log file.  Should we create our own error messages/codes?
#Pi will lose data if it has lost signal, read tags, then lost power before reconnecting to the DB.
	How can we correct this?


HTML:
#Make list of animals that visited feeder clickable.  Click calls pop-up that displays vitals.
#Validate input for all of our user fields.  **Need to validate Sire and Dam animal_id when adding to vitals.

#Create user login and authentications


24 Hour Maintenance:  
#Daily report including upcoming vaccination dates for animals, upcoming delivery dates, animals that have not visited the mineral feeder in 3 days.  




