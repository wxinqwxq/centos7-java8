# wxinqwxq/centos-java

This is a simple docker image for Oracle Java 8 based on a centos 7 image.

# Usage

You can use this image as a base image to install arbitrary java software in a Docker container. 
The JAVA_HOME environment variable will be set and java will be in the path.

Example run:

    docker pull centos:7.4.1708
    docker pull wxinqwxq/centos7-java8:jre8
    docker run -d wxinqwxq/centos7-java8:jre8 java -version

