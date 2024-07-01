# HNGAssignment1

<VirtualHost *:80>
    ServerAdmin webmaster@localhost
    ServerName 54.165.222.30

    DocumentRoot /var/www/gbengaokunniyi

    ErrorLog ${APACHE_LOG_DIR}/error.log
    CustomLog ${APACHE_LOG_DIR}/access.log combined

    <Directory /var/www/gbengaokunniyi>
        Options Indexes FollowSymLinks
        AllowOverride All
        Require all granted
    </Directory>

</VirtualHost>
