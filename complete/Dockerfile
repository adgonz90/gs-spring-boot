#
# Oracle Java 8 Dockerfile
#
# https://github.com/dockerfile/java
# https://github.com/dockerfile/java/tree/master/oracle-java8
#

# Pull base image.
FROM java:8

# Define working directory.
WORKDIR /data

ADD target/gs-spring-boot-0.1.0.jar .

# Define default command.
#CMD ["bash"]
CMD ["java", "-jar", "gs-spring-boot-0.1.0.jar"]