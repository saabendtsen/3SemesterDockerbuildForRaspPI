FROM arm32v6/tomcat:9-jre8-alpine
# FROM tomcat:9.0.37-jdk14-openjdk-slim

ADD context.xml /tmp

# https://jfrog.com/knowledge-base/tomcat-takes-forever-to-start-what-can-i-do/
ENV JAVA_OPTS="-Djava.security.egd=file:/dev/urandom"

