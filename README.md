# Java DevOps CI/CD

## Description

This is a simple Java application that uses Spring Boot to create a REST API. The application is containerized using Docker and can be deployed to a Kubernetes cluster.

## Prerequisites

- Java 17
- Maven
- Docker
- MySQL
- Kubernetes

## Installation

```bash
mvn clean install
```

## Run

```bash
java -jar target/demo-spring-app1-0.0.1-SNAPSHOT.jar
```

## Docker

```bash
docker build --build-arg JAR_FILE=build/libs/\*.jar -t demo-spring-app1 .
```

## Kubernetes

```bash
kubectl apply -f k8s/deployment.yaml
```
