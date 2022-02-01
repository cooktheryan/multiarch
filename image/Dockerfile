FROM registry.fedoraproject.org/fedora:latest
USER 0

RUN dnf -y install httpd && dnf clean all
ADD index.html /var/www/html

USER 1001
