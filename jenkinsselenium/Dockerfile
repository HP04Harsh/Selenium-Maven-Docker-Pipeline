FROM openjdk:17

WORKDIR /app

COPY . .

RUN apt-get update && apt-get install -y maven

RUN mvn -f jenkinsselenium/pom.xml clean install -DskipTests

CMD ["echo", "App Build Successful"]
