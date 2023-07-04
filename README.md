# server-ubuntu
IP: 192.168.87.23
pw: 12345678
------------------
mysqlserver=======
username : root
pass : 12345678
------------------
phpmyadmin==========
username: phpmyadmin
pass : 12345678

ftp===============
username : dmbhai
pass     : 123456

Need to know 
- how to expand disk
- how to change password in ftp, mysql,linux


linux=======
https://www.names.co.uk/support/articles/changing-your-root-password-on-an-ubuntu-server/

mysql=========
sudo mysql -u root -p
then 
enter current pass
after login
run this 
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '12345678';


then 
exit;

ftp==========
login root
sudo passwd username
