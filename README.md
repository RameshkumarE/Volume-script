sudo apt update
sudo apt install mysql-server
sudo systemctl start mysql.service
systemctl status mysql.service
sudo mysql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '12345';
exit
mysql_secure_installation


data file var
etc configuration
ensure service stop 
ensure delete all files
sudo apt remove mysql*
