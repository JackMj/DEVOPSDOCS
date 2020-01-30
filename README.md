# DEVOPSDOCS
Devops documentation

#Creating a docker file
--------------------------------------

#This is a sample Image 
FROM ubuntu 
MAINTAINER muzi.jack@gmail.com 

RUN apt-get update 
RUN apt-get install –y nginx 
CMD [“echo”,”Image created”]

--------------------------------------

#building an images

#build command
docker build


