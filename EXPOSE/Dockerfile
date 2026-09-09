FROM almalinux:9
RUN dnf install nginx -y
#as we give previously for creating multiple containers so we use 80port as we allow ingress rules to that
EXPOSE 80   
CMD ["nginx", "-g" ,"daemon off;" ]
