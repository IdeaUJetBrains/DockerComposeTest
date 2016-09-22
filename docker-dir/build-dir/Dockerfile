#======================================================================
# Tomcat
# Default port: 8080
# Working directory=CATALINA_HOME=/usr/local/tomcat/
# The application is deployed according to the container_settings.json here:
# http://192.168.99.100:18080/HelloDocker/
#======================================================================
FROM opavlova/tomcat
ARG olgatest-arg
RUN echo "Test: $olgatest-arg"
ADD HelloDocker.war $CATALINA_HOME/webapps/
