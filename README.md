# About this Repo

This is a fork repo from https://github.com/docker-library/php. 

The diffrent from the origin one is that :

* PHP in this docker is compiled with many usefull php-exts for delvelpment. So, don't use it for production.
* php-fpm.conf : `pm.start_servers = 1`

All Exts
------------

* apc (only for 5.4)
* bcmath
* bz2
* calendar
* Core
* ctype
* curl
* date
* dba
* dom
* ereg
* ev
* exif
* fileinfo
* filter
* ftp
* gd
* gearman
* gettext
* hash
* iconv
* igbinary
* imagick
* imap
* intl
* json
* libxml
* mbstring
* mcrypt
* memcache
* memcached
* mongo
* mysql
* mysqli
* mysqlnd
* openssl
* pcntl
* pcre
* PDO
* pdo_mysql
* pdo_pgsql
* pdo_sqlite
* pgsql
* phalcon <https://github.com/phalcon/cphalcon>
* Phar
* posix
* readline
* recode
* redis
* Reflection
* session
* shmop
* SimpleXML
* soap
* sockets
* solr
* SPL
* sqlite3
* standard
* swoole
* sysvmsg
* sysvsem
* sysvshm
* tidy
* tokenizer
* trace <https://github.com/Qihoo360/phptrace>
* wddx
* xhprof <https://github.com/phacility/xhprof>
* xml
* xmlreader
* xmlrpc
* xmlwriter
* xsl
* zip
* zlib
* Xdebug
* Zend OPcache

Pull
-----

You can directly use my images from docker hub: 

```
$ docker pull snowair/php-fpm:5.6
$ docker pull snowair/php-fpm:5.5
$ docker pull snowair/php-fpm:5.4
```

