# AlbumUsers
# create mysql DB and execute below commands to create database, user and  granting privileges  

mysql> create database root; </br>
mysql> create user 'root'@'%' identified by 'QAZwsx!234'; </br>
mysql> grant all on root.* to 'root'@'%'; </br>

mysql> create database albums; </br>
mysql> grant all on albums.* to 'root'@'%'; </br>

# starting profile with prod uses myqdl db and tables
