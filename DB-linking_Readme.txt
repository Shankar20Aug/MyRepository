Run - Command Prompt
Navigate to MySQL/bin
C:\> cd Progrm Files\MuSql\MySQL SErver 8.0\bin
C:\> mysql -u <username> -p
Enter Password: <password>

mysql> create database web_services; -- Create the new database
mysql> create user 'shankar'@'%' identified by 'shankar'; -- Creates the user identified by PAssword
mysql> grant all on web_services.* to 'shankar'@'%'; -- Gives all the privileges to the new user on the newly created database