# Usando imagem atual e mantida
FROM eclipse-temurin:11-jre-alpine

# Define o argumento com o caminho do JAR
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

# Copia o JAR para o container
COPY ${artifact} app.jar

# Comando de entrada
ENTRYPOINT ["java", "-jar", "app.jar"]

