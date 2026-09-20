FROM almalinux:9
#its not mandatory to use RUN mkdir /app for creating
RUN mkdir /app
#it will directly create app directory and pwd is /app
WORKDIR /app  
RUN echo "present working directory is ${PWD}"
CMD [ "sleep", "110" ]