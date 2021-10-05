FROM phpdockerio/php72-fpm:latest
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        git \ 
        php7.2-memcached \ 
        php7.2-mysql \ 
        php7.2-redis \ 
        php7.2-ssh2; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
