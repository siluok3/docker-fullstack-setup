# react-docker
Simple React with docker

To build the container: `docker build -t webapp:client .` 

To spin up the container: `docker run -it --rm -v ${PWD}:/client -v /client/node_modules -p 3000:3000 webapp:client`
