# helloworld19
# pull base image
From tomcat:8.jdk8
# Maintainer
MAINTAINER "kserge2001@yahoo.fr"
COPY ./webbapp/target/webapp.war/usr/local/tomcat/webapps
