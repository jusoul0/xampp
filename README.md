# xampp
Setting up a DB with PHP Mysql via xampp 

download installer and installer from https://www.apachefriends.org/download.html

replace the following files

xampp\htdocs\MyWebsite 

with the unzipped Mywebsite directory 

-------------------------------

run the following in http://localhost/phpmyadmin/ sqp tab

CREATE TABLE users (
	id INT(11) NOT NULL AUTO_INCREMENT,
    username VARCHAR(30) NOT NULL,
    pwd VARCHAR(255) NOT NULL,
   	email VARCHAR(100) NOT NULL,
    created_at DATETIME NOT NULL DEFAULT CURRENT_TIME,
    PRIMARY KEY (id)
);

-------------------------------

now acess http://localhost/MyWebsite/

