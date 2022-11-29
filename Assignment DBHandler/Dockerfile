FROM ubuntu:bionic 
#pull ubuntu
FROM gcc:latest 
#pull gcc
#just in case,  you can install gcc and cmake
#RUN apt-get update && apt-get -y install build-essentials gcc cmake
ADD . /usr/src 
# add (copy) all from local folder to /usr/src
WORKDIR /usr/src
EXPOSE 5555
RUN g++ Source.cpp -o Source
# comment this and un - comment other if you would like to run your # program manually from shell
CMD ["./Source"] 
#CMD ["/bin/bash"]