#Linux Server Configuration 03/08/2016

##README
------
- Linux Server Configuration Project, is project to develop a functions Linux Server to host the Catalog App developed in Project 3.  
- The Server has the following features
	- Apache 2:  HTTP Server
	- Postgres : Database
	- Flask 

----------------------------------------------------------------------------

## Setup Instructions
1. The server info is :
  - IP address : 52.27.102.4
  - ssh port : 2200
2. Connect to sever using the following command :
  - ssh -i ~/.ssh/udacity_key.rsa grader@52.27.102.4 -p 2200
3. Complete URL is : http://ec2-52-27-102-4.us-west-2.compute.amazonaws.com/

## Summary of software installed 
root@ip-10-20-55-1:~# history | grep "install" 

  251  sudo yum install git-all
  
  252  sudo apt-get install git-all
  
  301  pip install sqlalchemy
  
  358  yum list installed "postgres*"
  
  359  apt-get install yum
  
  360  yum list installed "postgres*"
  
  361  sudo apt-get install postgresql
  
  362  sudo apt-get install postgresql postgresql-contrib
  
  378  sudo apt-get install tree
  
  402  pip install psycopg2 Flask-SQLAlchemy Flask-Migrate
  
  404  pip install -U psycopg2
  
  428  easy_install flask-seasurf
  
  515  pip install Flask-SQLAlchemy
  
  608  pip install -U psycopg
  
  609  pip install -U psycopg2
  
  611  pip install -U psycopg2
  
  612  sudo apt-get install python-psycopg2
  
  638  sudo apt-get install postgresql
  
  687  sudo apt-get install ntp
  
  853  sudo pecl install oauth 
  
  854  apt-get install php-pear php5-dev
  
  855  pecl install oauth
  
  858  pecl install oauth
  
  859  pip install --upgrade oauth2client
  
  862  pip install dicttoxml
  
 1061  history | grep "install" 
 
 1154  history | grep "install" 
root@ip-10-20-55-1:~# 
