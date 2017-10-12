FROM centos
RUN yum -y update
RUN yum -y install httpd git
COPY index.html /var/www/html
VOLUME /var/www/html
VOLUME /var/log
CMD ["apachectl", "-D", "FOREGROUND"]
