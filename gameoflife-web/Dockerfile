FROM tomcat:8-jre8

RUN rm -rf /opt/apache-tomcat-8.5.34/webapps/*

COPY gameoflife-web/target/gameoflife.war /opt/apache-tomcat-8.5.34/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
