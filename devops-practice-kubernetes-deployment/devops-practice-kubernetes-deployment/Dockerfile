FROM tomcat:8.0.43-jre8
copy target/vprofile-v1.war /opt/tomcat/webapps/
EXPOSE 8080
CMD chmod +x /usr/local/tomcat/bin/catalina.sh
CMD ["catalina.sh", "run"]
