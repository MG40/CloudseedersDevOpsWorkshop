FROM centos:latest
RUN yum install httpd -y
COPY ./my-httpd.conf /etc/httpd/conf/httpd.conf
COPY index.html index.jpg /var/www/html/
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
