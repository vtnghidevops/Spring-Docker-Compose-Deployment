FROM openjdk:24-slim-bullseye


# Đặt thư mục làm việc trong container
WORKDIR /app

COPY spring-petclinic.jar /app/spring-petclinic.jar

EXPOSE 8080


CMD ["java", "-jar", "/app/spring-petclinic.jar"]
