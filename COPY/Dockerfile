FROM nginx
#from offical nginx image we remove default nginx webpage 
RUN rm -rf /usr/share/nginx/html/*
#Copying our index.html webpage to as nginx webpage
COPY index.html /usr/share/nginx/html/