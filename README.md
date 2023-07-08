# AlbumUsers
# create mysql DB and execute below commands to create database, user and  granting privileges  

mysql> create database root;
mysql> create user 'root'@'%' identified by 'QAZwsx!234';
mysql> grant all on root.* to 'root'@'%';

mysql> create database albums;
mysql> grant all on albums.* to 'root'@'%';

# starting profile with prod uses myqdl db and tables
