PHP 7.2, NGINX, REDIS, MYSQL 5.7, ELASTICSEARCH 7.12.1, KIBANA 7.12.1
==================================

- Build `docker-compose up -d`

## Outside Address
  - Webserver: [http://localhost:26000](http://localhost:26000)
  - MySQL:  `localhost:26001`
  - Kibana: [http://localhost:5656](http://localhost:5656)

## [Docker cheatsheet](https://dockerlabs.collabnix.com/docker/cheatsheet/)

## File Permission
`docker-compose exec php-fpm chown -R www-data:www-data /application/public`
