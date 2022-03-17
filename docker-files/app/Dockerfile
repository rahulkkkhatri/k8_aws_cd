FROM bitnami/tomcat:9.0
RUN rm -rf /opt/bitnami/tomcat/webapps/*

COPY profile.war /opt/bitnami/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps
