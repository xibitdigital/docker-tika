# docker-tikaserver
This repo contains the Dockerfile to create a docker image that contains the latest Ubuntu running the Apache Tika 1.14 Server on Port 9998 using Java 8.


## Usage

First you need to pull down the build from Dockerhub, which can be done by invoking:

    docker pull docker xibitdigital/tika

Then to run the container, execute the following command:

    docker run -d -p 9998:9998 docker xibitdigital/tika


## More

For more info on Apache Tika Server, go to the [Apache Tika Server documentation](http://wiki.apache.org/tika/TikaJAXRS).
