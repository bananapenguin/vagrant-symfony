FROM	php:7.2-apache
RUN	usermod -u 1000 www-data &&\
	groupmod -g 1000 www-data &&\
	a2enmod rewrite
COPY	000-default.conf /etc/apache2/sites-available/
