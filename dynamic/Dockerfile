FROM openjdk
EXPOSE 8080

ADD https://s3.amazonaws.com/infra-assessment/companyNews.war .
ADD http://central.maven.org/maven2/org/eclipse/jetty/jetty-runner/9.4.10.v20180503/jetty-runner-9.4.10.v20180503.jar jetty-runner.jar
CMD java -jar jetty-runner.jar companyNews.war
