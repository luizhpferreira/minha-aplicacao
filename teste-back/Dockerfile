# Use a imagem base do OpenJDK para Java 17
FROM openjdk:17-jdk-alpine

# Diretório de trabalho dentro do contêiner
WORKDIR /app

# Copie o arquivo JAR da aplicação para o contêiner
COPY ./target/teste-back-0.0.1-SNAPSHOT.jar /app/app.jar

# Porta que a aplicação expõe (ajuste conforme necessário)
EXPOSE 8080

# Comando para executar a aplicação quando o contêiner iniciar
CMD ["java", "-jar", "app.jar"]
