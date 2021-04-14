# helloworld19
# pull base image
From tomcat:8.jrc8
# Maintainer
MAINTAINER "ntube_diana@yahoo.com"
COPY ./webbapp/target/webapp.war/usr/local/tomcat/webapps
