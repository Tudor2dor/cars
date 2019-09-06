FROM centos:latest

RUN yum -y install httpd

ENTRYPOINT ["/usr/sbin/httpd", "-DFOREGROUND"]
EXPOSE 80
