FROM eclipse-temurin:21-jdk-jammy
# 빌드된 jar 파일을 컨테이너 내부로 복사
COPY target/*.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]