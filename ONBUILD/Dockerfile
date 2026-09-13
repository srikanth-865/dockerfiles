FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/*
ONBUILD COPY index.html /usr/share/nginx/html
CMD [ "nginx", "-g","daemon off" ]