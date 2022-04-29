FROM centos:7
RUN yum update -y && yum install httpd -y
RUN systemctl enable httpd
ADD index.html /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80
