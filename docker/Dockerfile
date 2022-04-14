FROM centos
RUN yum install httpd
RUN systemctl enable httpd
ENTRYPOINT ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80