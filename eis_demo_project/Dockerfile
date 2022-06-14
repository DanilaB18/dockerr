FROM tomcat:9.0.37-jdk11-adoptopenjdk-hotspot as build
LABEL maintainer="dborodulins@eisgroup.com"
COPY /usr/src/test2/eis_demo_project/target/web-app.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
