FROM nginx

USER root

COPY nginx.conf /etc/nginx/conf.d/default.conf

RUN chown -R www-data:www-data /var/www/html

WORKDIR /var/www/html/
 