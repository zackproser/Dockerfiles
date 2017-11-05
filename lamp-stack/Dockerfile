FROM ubuntu

LABEL maintainer="zackproser@gmail.com"

RUN apt-get update

RUN apt-get install php7.0 php7.0-fpm php7.0-mysql -y

ENV DEBIAN_FRONTEND="noninteractive"

RUN apt-get install mysql-server -y

RUN apt-get install nginx -y

RUN apt-get --purge autoremove -y
