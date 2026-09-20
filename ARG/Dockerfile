#we are passing version in build time its a special trick or ARG
ARG version
#if i dint pass anything by default it take version:9
FROM almalinux:${version:-9}
#it will use in build time but we can also override in build time by docker build  --build-arg course="devops" -t arg:v1 .
ARG course="docker" \
    duration="10hrs" 
#generally env is used for run time we can use those build time variables by taking to here to run those value time by using ENV

ENV course=${course} \
    duration=${duration}
#here we didnt get any version value becoz ARG works only before FROM instruction after from it doest have life it will die 
RUN echo "course is ${course} and time is in ${duration} and version is ${version}"
CMD [ "sleep", "110" ]