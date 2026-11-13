FROM almalinux:9
RUN dnf install -y nginx
RUN rm -rf /var/www/html/index.html
ONBUILD ADD index.html /var/www/html/index.html
CMD ["nginx","-g","daemon off;"]