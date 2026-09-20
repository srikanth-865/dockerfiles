
#we use os as almalinux it doesnt have any features to keep container still alive we have to give manually
FROM almalinux:9
#we are running nginx by locally we are give os almalinux 
RUN dnf install nginx -y
#this make to run command contiously without stopping otherwise it will start and close immediately
CMD [ "nginx", "-g" , "daemon off;" ]                                                                 nervous_kilby
