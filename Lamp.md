https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

1. sudo apt-get update 
#update the package
2. sudo apt-get install apache2 -y
# install apache2
3. sudo systemctl restart apache2 
# Restart apache2
4. sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql -y
# Install php
5. sudo systemctl restart apache2
# Restart apache2
6. Create a file @/var/www/html/info.php
    <?php
    phpinfo();
    ?>
7. Create a Home page