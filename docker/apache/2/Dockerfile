FROM php:7.2-apache

RUN mkdir /var/www/html/static
COPY index.php /var/www/html/static
RUN sed -ri -e 's!%O!%{ms}T %O!g' /etc/apache2/apache2.conf