FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY Wallet_A8QYE6TA3DEUCH8T /app/wallet
COPY target/*.jar app.jar

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "app.jar"]