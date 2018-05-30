FROM wordpress:latest

MAINTAINER saadrana219@gmail.com

RUN touch /usr/local/etc/php/conf.d/uploads.ini \
    && echo "upload_max_filesize = 150M;" >> /usr/local/etc/php/conf.d/uploads.ini

