# Instalasi Web Server

## Instalasi Apache2
```
sudo apt update
```
```
sudo apt install apache2
```
## Instalasi PHP 7.4 (Most Stable Version IMO)
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt install php7.4 php7.4-common php7.4-opcache php7.4-mcrypt php7.4-cli php7.4-gd php7.4-curl php7.4-mysql
```
## Check PHP version
```
php -v
```
## Instalasi MySQL
```
sudo apt install mysql-server mysql-client
```

# Tweak Web Server
```
a2enmod rewrite
```
