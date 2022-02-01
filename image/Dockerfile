FROM docker.io/fedora 
USER 0

RUN dnf -y install httpd && dnf clean all
ADD index.html /var/www/html

USER 1001
