Resetting mysql in case you forget your password/error

`systemctl stop mysql`
`sudo mysqld_safe --skip-grant-tables --skip-networking &`

make temporary mysqld

`mkdir -p /var/run/mysqld
chown mysql:mysql /var/run/mysqld`

login as root
`mysql -u root`

inside mysql

`mysql > FLUSH PRIVILEGES;
mysql > ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
mysql > FLUSH PRIVILEGES;`

then you can login using your old credential
