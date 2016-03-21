# Supported tags and respective Dockerfile links

- [`7.0`, (7.0/Dockerfile)][1]
- [`5.6`, (5.6/Dockerfile)][2]
- [`5.5`, (5.5/Dockerfile)][3]

[![](https://badge.imagelayers.io/melkorm/php-docker:latest.svg)](https://imagelayers.io/?images=melkorm/php-docker:latest 'Get your own badge on imagelayers.io')
[![Build Status](https://api.travis-ci.org/melkorm/php-docker.svg?branch=master)](https://travis-ci.org/melkorm/php-docker)

# PHP with composer and few most used extensions

## Extensions:

 - imagick
 - gd
 - iconv
 - soap
 - intl
 - mbstring
 - bcmath
 - iconv
 - mcrypt
 - zip
 - intl
 - xmlrpc


## Additional software:

 - composer
 - ssh
 - git

## TODO:

- make extensions / additional packages configurable
- ~~more PHP versions~~
- better tests to check if expected extensions / software is actually loaded

[1]: https://github.com/melkorm/php-docker/blob/master/7.0/Dockerfile
[2]: https://github.com/melkorm/php-docker/blob/master/5.6/Dockerfile
[3]: https://github.com/melkorm/php-docker/blob/master/5.5/Dockerfile
