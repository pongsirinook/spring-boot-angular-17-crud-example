FROM maven:3.9.8-sapmachine-22
COPY . .
RUN mvn clean package
EXPOSE 8080
CMD java -jar /target/spring-boot-jpa-h2-0.0.1-SNAPSHOT.jar
