FROM php:7.2-apache

COPY index.php /var/www/html/
RUN sed -ri -e 's!%O!%{ms}T %O!g' /etc/apache2/apache2.conf