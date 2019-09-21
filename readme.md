# Instalasi Web Server

## Instalasi Apache2
```
sudo apt update
```
```
sudo apt install apache2
```
## Instalasi PHP 7.1 (Most Stable Version IMO)
```
sudo apt update
```
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
```
sudo apt install php7.1 php7.1-common php7.1-opcache php7.1-mcrypt php7.1-cli php7.1-gd php7.1-curl php7.1-mysql
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
