


docker build -t halx4/php-builder:php7.4-composer2.4.4 .
docker image push halx4/php-builder:php7.4-composer2.4.4


docker login --username=halx4
docker image push halx4/php-builder:php7.4-composer2.4.4
