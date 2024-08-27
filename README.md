# simple-tiles

This spring-boot application describes how to use Apache Tiles as a view technology when deploying as a standalone self-executing WAR file. The important thing to note is that the application is packaged as a WAR file so it can be deployed in an application server (Tomcat, WebSphere, etc) but can still be run with `java -jar ...`

# Requirements

- JDK 17 or higher

# Compiling/Packaging

```
./mvnw clean package
```

# Running

```
java -jar target/simple-tiles-1.0.0.war
```
