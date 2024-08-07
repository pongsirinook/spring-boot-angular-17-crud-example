# Demo Docker Angular Spring
This is not my project, referent to it original [here](https://github.com/arctica-non/spring-boot-angular-17-crud-example) 

## Run Spring Boot application
```
cd angular-17-client
mvn clean package
java -jar /target/spring-boot-jpa-h2-0.0.1-SNAPSHOT.jar
```
The Spring Boot Server will export API at port `8080`.

## Run Angular Client
```
npm install
npm build
npm run start
```
Angular will start on port 8081
hello
