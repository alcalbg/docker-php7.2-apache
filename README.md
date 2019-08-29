# docker-php7.2-apache
Docker image with old php 7.2 running on apache2 with usual php extensions:

- php7.2
- php7.2-bcmath
- php7.2-curl
- php7.2-gd
- php7.2-mbstring
- php7.2-mysql
- php7.2-sqlite3
- php7.2-soap
- php7.2-xml
- php7.2-zip
- php7.2-xdebug

Based on Debian stretch

# sample usage
`docker run -d -v /var/www/html:/var/www/html -p 8000:80 alcalbg/php7.2-apache`

visit http://localhost:8000/
