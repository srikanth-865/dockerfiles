FROM almalinux:9
#means bydefault container RUN as root acces its danger security risk so we create our username 
RUN useradd roboshop
#by using this USER command it will change to user access instead of root
USER roboshop
CMD [ "sleep", "110" ]