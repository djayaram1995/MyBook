From java:8-jre
WORKDIR usr/src
ENV MYSQL_DATABASE=bookdb
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=root
ENV MYSQL_CI_URL=jdbc:mysql://localhost:3306/bookdb
ADD ./target/userservice.jar /usr/src/userservice.jar
EXPOSE 9876
ENTRYPOINT ["java", "-jar", "userservice.jar"]
