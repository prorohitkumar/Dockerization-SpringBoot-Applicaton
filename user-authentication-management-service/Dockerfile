FROM openjdk:11-jre-slim
WORKDIR usr/src
# ENV MONGO_URI=mongodb://localhost:27017/Soulmate
# EXPOSE 8888
ADD ./target/user-authentication-management-service-0.0.1-SNAPSHOT.jar /usr/src/user-authentication-management-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","user-authentication-management-service-0.0.1-SNAPSHOT.jar"]