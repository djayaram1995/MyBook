From java:8-jre
WORKDIR usr/src
ENV MYSQL_DATABASE=bookdb
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=root
ENV MYSQL_CI_URL=jdbc:mysql://localhost:3306/bookdb?useSSL=false
ADD ./target/favouriteservice.jar /usr/src/favouriteservice.jar
EXPOSE 8765
ENTRYPOINT ["java", "-jar", "favouriteservice.jar"]