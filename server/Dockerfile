arg php_version
from openswoole/swoole:php${php_version} as base

add https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/
copy ./docker/php.ini ${PHP_INI_DIR}/php.ini

run chmod a+x /usr/local/bin/install-php-extensions ;
run /usr/local/bin/install-php-extensions ds ;
