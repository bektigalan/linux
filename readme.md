# Instalasi Web Server

## Instalasi Apache2
```
sudo apt update
```
```
sudo apt install apache2
```

## Instalasi MySQL
```
sudo apt install mysql-server mysql-client -y
sudo mysql_secure_installation
```

## Instalasi PHP 7.4
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt install php7.4 phpmyadmin php7.4-common php7.4-opcache php7.4-mcrypt php7.4-cli php7.4-gd php7.4-curl php7.4-mysql phpmyadmin php7.4-mbstring php7.4-xml -y
```
## Check PHP version
```
php -v
```
## Tweak Web Server
```
a2enmod rewrite ssl
```
