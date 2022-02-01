FROM registry.fedoraproject.org/fedora:latest

RUN sudo dnf -y install httpd && yum clean all

ADD index.html /var/www/html
