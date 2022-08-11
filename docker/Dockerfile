FROM centos:7
RUN yum install httpd -y
ENV user=Vishnu
COPY index.html /var/www/html/
ENTRYPOINT  [ "/bin/sh", "-c", "/usr/sbin/httpd && bash " ]
