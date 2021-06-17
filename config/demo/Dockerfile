FROM tomcat:8.0-alpine

ENV WEBAPPS=/usr/local/tomcat/webapps/

ADD autocomplete.war $WEBAPPS

EXPOSE 8080

CMD ["catalina.sh", "run"]
