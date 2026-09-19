FROM almalinux:9
RUN dnf install nginx -y
#as we give previously for creating multiple containers so we use 80 port as our host port so the 80 port is used in security group ingress rules allowing
#so if wee see inspect with our image name  we get expose mao key value
EXPOSE 80   
CMD ["nginx", "-g" ,"daemon off;" ]
