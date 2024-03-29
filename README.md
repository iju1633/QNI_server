# QNI (Question aNd I)

![Java](https://img.shields.io/badge/Java-4285F4?style=flat-square&logo=Java&logoColor=white)
![Spring-Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=Spring-Boot&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-FFCC00?style=flat-square&logo=Swagger&logoColor=white)
![RDS](https://img.shields.io/badge/Amazon_RDS-4285F4?style=flat-square&logo=Amazon-RDS&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-4285F4?style=flat-square&logo=Amazon-EC2&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-4285F4?style=flat-square&logo=Docker&logoColor=white)

This application asks you questions to help you understand yourself.

## 📖 Explanation

Many people cannot easily answer the question of who they are.

Accordingly, I thought it would be nice if there was a service that asked questions that could help me get to know myself.  
In addition, the accumulated data can be used as a tool to share with loved ones in the future.

## 🖥️ UI Design
[Figma Link](https://www.figma.com/file/ZY0M8jz6apBFTpYiXe5H4s/%ED%8C%8C%EC%9D%B4%ED%94%84-%EC%BD%94%EB%94%A9-%ED%81%B4%EB%9F%BD_%EA%B3%BC%EC%A0%9C?node-id=0%3A1&t=4G5qNN3cJOKI6Jc5-1)

## 💎 Main Features

- HTTP REST API Server configured With Spring Boot Application.
- Deploying using docker and dockerhub.
- DB management using Amazon RDS.

## 📐 Deployment/Diagram
![image](https://user-images.githubusercontent.com/43805087/213965765-3cb45361-1419-4f37-b6ae-6580a0c0b167.png)

- Build with Gradle.
- Build Jar file, Make Docker Image and deploy it using docker in Amazon EC2 instance.
- Using Amazon RDS to manage DB easily.

## 🖥️ Build Environment
This project uses Gradle, Amazon EC2, and Docker.
To build and run this project, first build `.jar` with Gradle, and build docker image and push it to dockerhub.  
After that, pull the image in Amazon EC2 and deploy it with docker.

## 📃 API Specification

[Swagger Link](http://3.35.39.43/swagger-ui/#/)  
This project utilize swagger Specification 2.0 and Swagger UI for communication with client.  
![api 명세서](https://user-images.githubusercontent.com/43805087/211522965-e428082d-c009-4834-9300-d6e5f6e8e494.png)

## 🏛️ Depedency Used
- implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
- implementation 'org.springframework.boot:spring-boot-starter-security'
- implementation 'org.springframework.boot:spring-boot-starter-validation'
- implementation 'org.springframework.boot:spring-boot-starter-web'
- implementation 'io.springfox:springfox-boot-starter:3.0.0'
  
#### Contributor

[Jaeuk Im](https://github.com/iju1633)
|:---:|
|BACKEND|
